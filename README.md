# Cloud Insurance Co. - Overview

Cloud Insurance Co. is a modern insurance company for the 21st century.

The following projects are leveraged in the overall Cloud Insurance Co. solution:

* [insurance-catalog][catalog_github_url] - An API to retrieve and update a catalog of insurance policies
* [insurance-orders][orders_github_url] - An API to retrieve and update a list of insurance policy orders made by customers
* [insurance-bot][bot_github_url] - UI that provides a chat bot interface for users to query their health benefits and file claims.
* [insurance-bot-dashboard][dashboard_github_url] - A user interface showing an history of the bot chats for further analysis.
* [insurance-bot-ios][mobile_github_url] - An iOS application for the chat bot.

## Code Status

| :point_down: Repositories ... Branches :point_right: | master | dev |
| --- | :--- | :--- |
| [insurance-bot][bot_github_url] | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-bot.svg?branch=master)](https://travis-ci.org/IBM-Bluemix/insurance-bot) | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-bot.svg?branch=dev)](https://travis-ci.org/IBM-Bluemix/insurance-bot) |
| [insurance-orders][orders_github_url] | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-orders.svg?branch=master)](https://travis-ci.org/IBM-Bluemix/insurance-orders) | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-orders.svg?branch=dev)](https://travis-ci.org/IBM-Bluemix/insurance-orders) |
| [insurance-catalog][catalog_github_url] | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-catalog.svg?branch=master)](https://travis-ci.org/IBM-Bluemix/insurance-catalog) | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-catalog.svg?branch=dev)](https://travis-ci.org/IBM-Bluemix/insurance-catalog) |
| [insurance-bot-dashboard][dashboard_github_url] | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-bot-dashboard.svg?branch=master)](https://travis-ci.org/IBM-Bluemix/insurance-bot-dashboard) | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-bot-dashboard.svg?branch=dev)](https://travis-ci.org/IBM-Bluemix/insurance-bot-dashboard) |
| [insurance-bot-ios][mobile_github_url] | [![Build Status](https://travis-ci.org/IBM-Bluemix/insurance-bot-ios.svg?branch=master)](https://travis-ci.org/IBM-Bluemix/insurance-bot-ios) | - |

## Deploy

To deploy the full system all at once, check out the [Cloud Insurance Co. Toolchain][toolchain_github_url]

## Architecture

  ![Architecture Diagram](architecture.png)

  Visit the [wiki](https://github.com/IBM-Bluemix/cloudco-insurance/wiki) for more details on Cloud Insurance Co. architecture and components.

## License

See [License.txt](License.txt) for license information.

# Privacy Notice

The application is configured to track deployments to [IBM Bluemix](http://www.ibm.com/cloud-computing/bluemix/) and other Cloud Foundry platforms. Refer to the individual projects to understand what information is tracked and how to disable the tracking.

[bot_github_url]: https://github.com/IBM-Bluemix/insurance-bot
[orders_github_url]: https://github.com/IBM-Bluemix/insurance-orders
[catalog_github_url]: https://github.com/IBM-Bluemix/insurance-catalog
[dashboard_github_url]: https://github.com/IBM-Bluemix/insurance-bot-dashboard
[mobile_github_url]: https://github.com/IBM-Bluemix/insurance-bot-ios
[toolchain_github_url]: https://github.com/IBM-Bluemix/insurance-toolchain
