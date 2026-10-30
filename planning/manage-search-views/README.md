---
description: >-
  Build custom appointment lists (MySearch) and choose which ones appear on the
  home screen.
---

# Manage search views

The view manager lets you create custom lists, called **MySearch**. Each list can display appointments that meet your chosen criteria.

For each view, you can define:

* The filters used to select appointments.
* The columns and their order.
* Available row and bulk actions.
* Options such as the list name, maximum results, and the home-screen counter.

### The two view types

|                         | Administrator view (general MySearch) | User view                        |
| ----------------------- | ------------------------------------- | -------------------------------- |
| **Who it is for**       | Shared by all users                   | Personal                         |
| **Tab**                 | **General searches**                  | **User**                         |
| **Creation**            | 15 fixed slots                        | **Add a search** in MySearch     |
| **Copy or delete**      | No. Reconfigure the slot.             | Yes. Use **Copy** or **Delete**. |
| **Name**                | Optional                              | Required                         |
| **Required permission** | `1445`                                | `1446`                           |

### Prerequisites

The following permissions control access to view management:

| Permission       | Description                                                     | Access                                                                             |
| ---------------- | --------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `1445`           | Allows editing application view customizations.                 | **General searches**, **Unavailabilities**, and **Projects**. Administrator views. |
| `1446`           | Allows creating, editing, and viewing user view customizations. | **User** tab. Personal views.                                                      |
| `1433`           | Allows editing view customizations.                             | Displays **Edit MySearch**.                                                        |
| `1330` to `1344` | Access to appointment MySearch lists.                           | Appointment MySearch lists.                                                        |
| `1352` to `1356` | Access to unavailability MySearch lists.                        | Unavailability MySearch lists.                                                     |

{% hint style="info" %}
The **View managers** menu appears only with permission `1445` or `1446`. Only users with permission `1446` can access the **User** tab.
{% endhint %}

### Access the view manager

1. Go to **Planning**.
2. Open the **Planning** menu.
3. Select **View managers**.
4. Choose the relevant module and entry.

![View managers menu](/broken/files/ka97Ucad11ytVQR3HwxK)

### Available tabs

| Tab                  | Content                                              | Permission | Default views    |
| -------------------- | ---------------------------------------------------- | ---------- | ---------------- |
| **General searches** | General MySearch lists, alerts, and status searches. | `1445`     | MySearch 1 to 15 |
| **User**             | Personal appointment views.                          | `1446`     | —                |
| **Unavailabilities** | Unavailability MySearch lists.                       | `1445`     | MySearch 1 to 5  |
| **Projects**         | Project views.                                       | `1445`     | —                |

![General searches tab](/broken/files/HN1krtVcvKo44hf2OkeB)

![User tab](/broken/files/qJqUo0ceRTVkOjyZHkZs)

![Unavailabilities tab](/broken/files/N9tJbnqU4baGB9oE6IH8)

![Projects tab](/broken/files/6Xm00QRO2DKXtwyvKMZr)

### Edit a view directly from a results list

The **Edit MySearch** action opens the configuration wizard. It is available with permission `1433`.

### Choose views for the home screen

1. Select the relevant tab.
2. Select or clear the **Home page** column for each view.
3. Select **Save changes**.

![Choose home-page views](/broken/files/bCAmvASIHYiUIANB3B19)

### Related pages

* [Configure a view with the wizard](configure-a-view-with-the-wizard.md)
* [Create an administrator view](create-an-administrator-view.md)
* [Create a user view](create-a-user-view.md)
* [Edit, copy, or delete a view](edit-copy-or-delete-a-view.md)
