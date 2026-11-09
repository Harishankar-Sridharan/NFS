---
description: Set up automatic PDF report generation.
---

# How do I set up automatic PDF appointment reports?

1. **Assign permissions.** In **Administration > Users > Permission collection**, open the **Reports** tab and select the `REPORTMANAGEMENT_*` permissions you need. For profiles that publish reports, open the **Scheduling** tab, then the **Appointments** section, and select `CALLCENTER_PUBLISH_REPORT`. Select **Save**.
2. **Upload the template.** In **Report > Report template**, select **New**, enter a **Name**, select the file, then select **Add**.
3. **Enable generation.** In **Administration > Customization > Application configuration**, filter for `triggerPrepareReport`, set the **appointment.completion.agent.activation** node to **on**, then select **Save**.

When an appointment changes to **Completed**, a PDF is generated if none is already attached.

{% hint style="warning" %}
The application configuration change applies to all users. Have it approved by an environment administrator.
{% endhint %}
