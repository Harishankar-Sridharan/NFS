# Running the Application

## Overview

You can access NFS through a web browser or the mobile application, depending on the deployment.

## Access NFS in a web browser

1. Open a supported web browser.
2. Enter the NFS URL provided by your site administrator. The URL typically has the following format: `http://server:port/application/`
3. Enter your login credentials when prompted.

![Access portal](../.gitbook/assets/sso-01.png)

Once you have entered your credentials, you gain access to the application.

## Access NFS in the mobile application

1. Open the NFS mobile application.
2. Enter the **login** and **password** associated with your user account.
3. Sign in to access the application.

## Authenticate through Single Sign-On (SSO)

This section describes a sample authentication use case.

{% hint style="warning" %}
Prerequisites: enable SSO and its Google Apps provider only, in the application instance settings.
{% endhint %}

### Sign in with Google

1. Open the NFS application URL in your web browser.
2. On the login page, click **Login with Google**.
3. You are redirected to the Google sign-in page to authenticate with your Google account.
4. Enter your Google account credentials and complete the authentication process.
5. After successful authentication, you are redirected to the NFS application.

![Login page with the Google sign-in option](../.gitbook/assets/sso-01.png)

* Enter your Google Workspace or Gmail account credentials and submit the form. If the credentials are valid, you are authenticated and redirected back to the NFS application.

![Google account sign-in page](../.gitbook/assets/sso-02.png)

![Google account authentication step](../.gitbook/assets/sso-03.png)

* If no NFS user account is associated with your Google account email address, access to the application is denied.

![Access denied message](../.gitbook/assets/sso-05.png)

* If an NFS user account is associated with your Google account email address, NFS grants access using the corresponding user account.

## Sign in to the application

Once you are authenticated, NFS redirects you, depending on your profile, to one of the following modules: [Portal](../portal/README.md), [Planning](../planning/README.md), [Supervisor](../planning-1/README.md), [Attendance](../attendance/README.md), the Strategic module or [Administration](../administration/README.md).

{% hint style="info" %}
See also: EXPLOITATION > Configuring SSO access in NFS, and REFERENCE GUIDE > Administration > Company data > Human resources > [Company Data](../administration/companydata.md) (**User** tab).
{% endhint %}
