<h1 align="center">Configuration History</h1>
<h2 align="center">"Trust, but verify"</h2>

Magento 2 module for recording changes in the Magento 2 Configuration.
This gives you insight in Who changed What, When & How.

## Installation

```bash
composer require danielriezebos/configurationhistory
bin/magento setup:upgrade
```

> Quick-warning: This module is still early in development.
> Things might be subject to change. Use/change at your own leisure.

## How to use

When the module is installed changes in the Magento 2 configuration will be recorded to the table `core_config_history`.
These recordings will be shown in the Configuration History page found at `Stores > Settings > History`.
The usual filtering and pagination are available in the necessary listing.

There are plans to improve this listing by separating the Message column into several columns, allowing for more precise filtering.
I'll build that when I get around to it. ;)

## Support

Feel free to fork this project, create a pull-request or send in issues! Consider that this project is built in spare-time and might not receive to many updates.
