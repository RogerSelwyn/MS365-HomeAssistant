---
title: Installation and Configuration
nav_order: 4
---

# Installation and Configuration
## Installation
1. Ensure you have followed the [prerequisites instructions](./prerequisites.md)
    * Ensure you have a copy of the Client ID and the Client Secret **Value** (not the ID)
1. Optionally you can set up the [permissions](./permissions.md), alternatively you will be requested to approve permissions when you authenticate to MS 365.
1. Install this integration via HACS:
1. Launch HACS
    1. Search for "Microsoft 365 xxxxxxxxx" (where xxxxxxxxx is the specific integration)
    1. Select "Download"
    1. Restart Home Assistant
    1. Go to the Home Assistant Devices configuration page
    1. Click "Add Integration"
    1. Search for "Microsoft 365 xxxxxxxxx"
    1. Click on the result, and follow the prompts.
1. Restart your Home Assistant instance to enable the integration
1. Add the integration via the `Devices & Services` dialogue. Follow the instructions in the install process (or see [Authentication](./authentication.md)) to establish the link between this integration and the Entra ID App Registration
    * A persistent token will be created in the hidden directory config/ms365_storage/.MS365-token-cache

**Note** If your installation does not complete authentication, or the sensors are not created, please go back and ensure you have accurately followed the steps detailed, also look in the logs to see if there are any errors. You can also look at the [errors page](./errors.md) for some other possibilities.

**Note** To configure a second account, add the integration again via the `Devices & Services` dialogue.

For detail on configuration for the individual integrations, please see the pages below:

The detailed permissions for each integration are shown here:
* [MS365 Calendar](https://rogerselwyn.github.io/MS365-Calendar/installation_and_configuration.html)
* [MS365 Contacts](https://rogerselwyn.github.io/MS365-Contacts/installation_and_configuration.html)
* [MS365 Mail](https://rogerselwyn.github.io/MS365-Mail/installation_and_configuration.html)
* [MS365 Teams](https://rogerselwyn.github.io/MS365-Teams/installation_and_configuration.html)
* [MS365 To Do](https://rogerselwyn.github.io/MS365-ToDo/installation_and_configuration.html)