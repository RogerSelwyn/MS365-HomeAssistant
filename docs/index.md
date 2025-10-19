---
title: Home
nav_order: 1
---

# Overview
These are the integrations that make up the full MS365 suite. It is made up of:
* [MS365 Calendar](https://github.com/RogerSelwyn/MS365-Calendar)
* [MS365 Contacts](https://github.com/RogerSelwyn/MS365-Contacts)
* [MS365 Mail](https://github.com/RogerSelwyn/MS365-Mail)
* [MS365-Teams](https://github.com/RogerSelwyn/MS365-Teams)
* [MS365-ToDo](https://github.com/RogerSelwyn/MS365-ToDo)

All the integrations are built to the same standard with the same authentication and configuration mechanism. All the integrations can use the same Entra ID App Registration and secret if desired.

This project would not be possible without the wonderful [python-o365 project](https://github.com/O365/python-o365).

# Microsoft 365 Home Assistant Documentation

This repository provides the foundational guides for all the integrations. Integration specific detail is provided in the documentation for the specific integration and is linked to from this guide. In general:-
1. [Prerequisites](./prerequisites.md) - Guidance on how to setup Entra ID App Registration
1. [Permissions](./permissions.md) - Optionally pre-add permissions as required by the integration. Required permissions will be requested at authentication time if not already granted.
1. [Installation](./installation_and_configuration.md) - Install the integration into Home Assistant.
1. [Authentication](./authentication.md) - Authenticate to your Microsoft 365 account, and authorise access permissions (if required).

Additionally 
* [Errors](./errors.md) - Errors you may see, and what to do
* [Events](./events.md) - The various integrations raise HA Events, which can be used to trigger automation
* [Services](./services.md) - Integration specific services, typically for update actions
* [Token](./token.md) - Information regarding tokens

Within each repository there is also information relevant to the indidual integration.
* [MS365 Calendar Documentation](https://rogerselwyn.github.io/MS365-Calendar/)
* [MS365 Contacts Documentation](https://rogerselwyn.github.io/MS365-Contacts/)
* [MS365 Mail Documentation](https://rogerselwyn.github.io/MS365-Mail/)
* [MS365 Teams Documentation](https://rogerselwyn.github.io/MS365-Teams/)
* [MS365 To Do Documentation](https://rogerselwyn.github.io/MS365-ToDo/)