---
description: Use merge fields in a Word report template.
---

# How do I add appointment data, photos, and signatures to a Word report template?

Write the fields in Freemarker syntax:

* To insert a field, press **Ctrl + F9**, right-click the field, select **Edit Field…**, choose **MergeField**, and enter the variable.
* Loop through appointments with `[#list appointments as appt]`, then display values such as `${appt["CUSTOMERID.CUSTOMERNAME"]}`.
* Resources who completed the appointment are in `ACHIEVEMENT_RESOURCES`, separated by semicolons.
* To repeat a table row, put the `@before-row` and `@after-row` tags in the first cell.
* Form responses are stored as JSON and retrieved by appointment identifier, then form title.
* Photos come from `mmPhotos`, and handwritten signatures from `mmRootPhotos`, with the `photo`, `workerSignature`, and `clientSignature` bookmarks on the image placeholders.

Available data names are listed in **Administration > CSV files > CSV import/export model**.

{% hint style="info" %}
Retrieving signatures requires an application version later than 2025.2.14. Displaying the signer name requires mobile application version 1.8.0.
{% endhint %}
