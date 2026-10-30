---
description: >-
  Manage profiles, permission collections, access rights, and alert
  subscriptions.
---

# Manage profiles and permissions

A user's permissions are defined at three levels:

* an **access right** authorizes a specific action, such as creating a region;
* a **permission collection** groups access rights, module by module;
* a **profile** combines one or more permission collections. It is assigned on the **User** tab of a human resource record.

## Before you begin

These pages change what users can see and do. Test every change with a test account before applying it to active profiles.

## Access the feature

| Entry                 | Navigation                                       |
| --------------------- | ------------------------------------------------ |
| Profile               | `Administration > Users > Profile`               |
| Permission collection | `Administration > Users > Permission collection` |
| Access rights         | `Administration > Users > Access rights`         |
| Alert subscription    | `Administration > Users > Alert subscription`    |

## Manage a profile

The list displays each profile's **Name**, **Region**, and **Description**.

![Profile list](/broken/files/CDExjiDNrwEA6JlD4jsf)

1. Select **Create a profile**, or select a row.
2. In **Information**, enter the **Name**, then, if needed, the **Abbreviation** and **Description**.
3. Select **Save**.

![Profile Information tab](/broken/files/9btA4fV8JiMeqimCn6jC)

The **Collections** tab lists the profile's **Permission collections**:

* **Add** attaches a collection;
* to remove a collection, select it in the **Delete** column, then select **Delete**.

![Profile Collections tab](/broken/files/aaDtMt1KBx8195mo1yEB)

## Manage a permission collection

1. Select **Create a permission collection**, or select a row.
2. Enter the **Name**, then, if needed, the **Abbreviation** and **Description**.
3. Select the module tab to configure: **Planning**, **Portal**, **Supervisor**, **Availabilities**, **Administration**, **Doc**, or a module in the **Modules** menu (**Strategic planning**, **Sectorization**, **Fulfilment**, **Tracking**, **Restricted access zones**, **Stock management**, **Reports**). The **My applications** menu provides access to additional applications.
4. In each section, select the rights to grant in the **Sel.** column.
5. Select **Save**.

![Permission collection, Planning tab](/broken/files/muf1QQ4uYJEwUf3ZR7qY)

Rights are grouped in expandable sections, for example **Scope**, **Schedule**, **Customer**, **Appointment**, or **Optimization**. The **Show all / Hide all** link opens or closes every section. Each row displays the right's technical name and **Description**.

## View access rights

The **Access rights** page lists available rights with their **Name** and **Description**. Choose the **Module** to display its rights: **Administration**, **Planning**, **Portal**, **Supervisor**, **Availabilities**, **Sectorization**, **Fulfilment**, **Doc**, and more.

![Administration access-right list](/broken/files/fArht1nqtEowb4Wdoj9v)

## Manage alert subscriptions

The **Application alert subscriptions** page defines which users receive application alerts.

1. Choose the target: **Profile** or **Permission collection**, then select the value from the list.
2. Choose the alert **Type**, for example **Error during import** or **Batch optimization warning**, or `--All--`.
3. Choose the **Logging level**.
4. Select **Add**.

The subscription is created as soon as you select **Add**. It appears in the list with the **Profile**, **Permission collection**, **Type**, and **Logging level**.

![Application alert subscriptions](/broken/files/1YyVzA6hLWdTBcX3Jwra)

To delete a subscription, select its row in the **Delete** column, then select **Delete**.

{% hint style="warning" %}
Check the target, type, and level before selecting **Add**. No confirmation is requested.
{% endhint %}

## Things to note

* To assign a profile to a user, see the **User** tab in [Manage human resources](manage-human-resources.md).
* Administration-module rights are in the collection's **Administration** tab, and are listed in **Access rights** with the `Administration` module.
