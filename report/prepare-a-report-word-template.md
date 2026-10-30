---
description: Prepare a Word appointment report template with merge fields.
---

# Prepare a report Word template

A report template is a Word document. It contains merge fields that are replaced by appointment data when the PDF is generated. Fields use Freemarker template syntax.

## Before you start

Available data names follow the Nomadia Field Service data model. View them in `Administration > CSV files > CSV import/export model`.

## Add a merge field in Word

1. Place the cursor where you want the field in the Word document.
2. Press **Ctrl + F9** to insert a field.
3. Right-click the new field and select **Edit Field…**.
4. In **Field names**, select **MergeField**.
5. In **Field name**, enter the variable, for example `${APPOINTMENT.APPOINTMENTID}`.
6. Confirm.

Examples of variables:

| Variable                       | Data                   | Example result                      |
| ------------------------------ | ---------------------- | ----------------------------------- |
| `${APPOINTMENT.CUSTOMERID}`    | Customer identifier    | CLI-0001                            |
| `${APPOINTMENT.APPOINTMENTID}` | Appointment identifier | Appointment\_0000001\_20260101-1000 |

## Iterate through report appointments

A report can contain several appointments. Iterate through them with a list:

```
[#list appointments as appt][#assign apptId=appt.APPOINTMENTID]
  ...
[/#list]
```

### Display the customer name

```
${appt["CUSTOMERID.CUSTOMERNAME"]}
```

### Display the resource who completed the appointment

Resources who completed the appointment are in the `ACHIEVEMENT_RESOURCES` collection. Entries are separated by a semicolon:

```
[#list appt["ACHIEVEMENT_RESOURCES()"]?split(";") as achievResources]
${appt["ACHIEVEMENT_RESOURCES(${achievResources?index}).RESOURCEFIRSTNAME"]} ${appt["ACHIEVEMENT_RESOURCES(${achievResources?index}).RESOURCELASTNAME"]}
[/#list]
```

## Display a list in a table

To repeat a Word table row, place the `@before-row` and `@after-row` tags in the first cell. They open and close the list on that row, avoiding unclosed tags.

Example: list appointment products with `productOrder` details:

```
@before-row[#list appt["APPOINTMENTDETAILS()"]?split(";") as apptDetails]
[#if appt["APPOINTMENTDETAILS(${apptDetails?index}).KIND"] == "productOrder"]
${appt["APPOINTMENTDETAILS(${apptDetails?index}).PRODUCTID"]}
@after-row[/#if][/#list]
```

The other cells in the row contain fields to display, such as product description and quantity.

## Include form responses

Responses from **Report** module forms are stored as JSON. Retrieve them with the appointment identifier, then the form title:

```
[#if jsonSurveyResults[apptId]??]
  [#assign json=jsonSurveyResults[apptId]]
  [#if json["Form title"]??]
    ${json["Form title"].question1!}
  [/#if]
[/#if]
```

* Replace `Form title` with the form title in Nomadia Field Service.
* Replace `question1` with the question name in the form.

### Multiple-choice question

For a checkbox question, the response is a list of values. Iterate through it and display each value label:

```
[#assign answers = json["Form title"].question3]
[#list answers as answer]
[#if answer=='Item 1']Label 1[#elseif answer=='Item 2']Label 2[/#if]
[/#list]
```

### Yes / No question

```
[#if json["Form title"].question2]Yes[#else]No[/#if]
```

## Insert photos and signatures

Two image sets are available for an appointment:

| Set            | Content                                                                      |
| -------------- | ---------------------------------------------------------------------------- |
| `mmPhotos`     | Photos from the appointment's **Images** folder                              |
| `mmRootPhotos` | Images at the root of the appointment folder, such as handwritten signatures |

Example condition to display photos only when the appointment contains them:

```
[#if mmPhotos[apptId]?size gt 0]
  [@printAppointmentPhotos appt 90 /]
[/#if]
```

The `printAppointmentPhotos` macro must be declared in the template. In the Word document, the image used as the photo placeholder must have the `photo` bookmark.

For handwritten signatures, the template declares a macro for the technician signature and another for the customer signature. Their image placeholders have the `workerSignature` and `clientSignature` bookmarks.

### Display the signer name

```
[#macro printClientSignataire signRows][@initSize id="signRows" bookmark="clientSignature"/]
[#list signRows as row][#if row.isClientSignature]
${row.clientSignatory}
[/#if][/#list]
[/#macro]

[@printClientSignataire mmRootPhotos[apptId]/]
```

{% hint style="info" %}
Retrieving handwritten signatures requires an application version later than 2025.2.14. Displaying the signer name requires mobile application version 1.8.0.
{% endhint %}
