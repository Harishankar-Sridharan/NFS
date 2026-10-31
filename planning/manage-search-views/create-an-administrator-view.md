---
description: Configure a MySearch view shared by several users.
---

# Create an administrator view

An administrator view provides a shared appointment list for a group of users. For example, use it for “Appointments to confirm D+2” for the whole planning team.

{% hint style="info" %}
**Prerequisite:** permission `1445` — allows editing application view customizations.
{% endhint %}

## Access the feature

**Navigation:** `Planning > Planning menu > View managers > General searches tab`

## Configure the view

1. Open **View managers**. The **General searches** tab appears.
2. Find an unused MySearch. It still has the default name **MySearch N appointment list**. Note its number, N.
3. Select that row’s pencil icon, **Edit**. The **Edit MySearch** wizard opens.
4. Complete **Filters**, **Columns**, **Optional actions**, and **Bulk actions**. For details, see [Configure a view with the wizard](configure-a-view-with-the-wizard.md).
5. On the **Proceed** step, enter a meaningful **Name**. This name appears in every user’s menu.
6. Select **Save changes**, then close the window.
7. Optional: show the view as a card on the home screen. Select the row’s **Home page** checkbox, then select **Save changes** at the top of the page.
8. Give the users who need the view the **Access to MySearch N appointment list** permission. Use the same number, N.

The view replaces “MySearch N appointment list” in the **Appointments** menu for users with access.

{% hint style="warning" %}
Without the **Access to MySearch N appointment list** permission, the view does not appear in any user’s menu, even when it is configured correctly.

Administrator views cannot be deleted. To effectively remove one, revoke users’ access permission or configure the slot for another purpose.
{% endhint %}

## Unavailability and project views

The **Unavailabilities** tab, with unavailability MySearch 1 to 5, and the **Projects** tab work the same way. Select the row’s pencil icon, configure the view, then save it. For unavailabilities, give users the corresponding **Access to MySearch N unavailability list** permission.
