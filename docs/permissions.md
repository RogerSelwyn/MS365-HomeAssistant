---
title: Permissions
nav_order: 3
---

# Permissions

You may wish to pre-add permissions to your Entra Id application so they apply to all users of that application. If you don't the required permissions will be requested when the user authenticates to Microsoft 365.

Under "API Permissions" click `Add a permission`, then `Microsoft Graph`, then `Delegated` permission, and add the permissions as detailed in the list and table below:
  * Update - Where the table indicates Y in the Update column, this permission is required if update functionality is enabled on the integration - typically be ticking `Enable update services`.
  * Shared - Where the permission ends in `.Shared` this is where access to a shared mailbox has been configured - by putting an email address or ID in the `Email address/ID of 'shared' mailbox` field. Do not put your login email address in this box.

The detailed permissions for each integration are shown here:
* [MS365 Calendar](https://rogerselwyn.github.io/MS365-Calendar/permissions.md)
* [MS365 Contacts](https://rogerselwyn.github.io/MS365-Contacts/permissions.md)
* [MS365 Mail](https://rogerselwyn.github.io/MS365-Mail/permissions.md)
* [MS365 Teams](https://rogerselwyn.github.io/MS365-Teams/permissions.md)
* [MS365 To Do](https://rogerselwyn.github.io/MS365-ToDo/permissions.md)

## Changing Features and Permissions
If you decide to enable new features in the integration, or decide to change from read only to read/write, you will very likely get a warning message similar to the following in your logs.

`Minimum required permissions not granted: ['Tasks.Read', ['Tasks.ReadWrite']]`

You will need to delete the token as detailed on the [token page](./token.md)
