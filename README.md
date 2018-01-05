# Cloud Insurance Co. - Overview

Cloud Insurance Co. is a modern insurance company for the 21st century.

The following projects are leveraged in the overall Cloud Insurance Co. solution:

* [insurance-catalog][catalog_github_url] - An API to retrieve and update a catalog of insurance policies
* [insurance-orders][orders_github_url] - An API to retrieve and update a list of insurance policy orders made by customers
* [insurance-bot][bot_github_url] - UI that provides a chat bot interface for users to query their health benefits and file claims.
* [insurance-bot-dashboard][dashboard_github_url] - A user interface showing an history of the bot chats for further analysis.
* [insurance-bot-ios][ios_github_url] - An iOS application for the chat bot.
* [insurance-bot-android][android_github_url] - An Android application for the chat bot.

## Code Status

| :point_down: Repositories ... Branches :point_right: | master | dev |
| --- | :--- | :--- |
| [insurance-bot][bot_github_url] | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-bot.svg?branch=master)](https://travis-ci.org/IBM-Cloud/insurance-bot) | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-bot.svg?branch=dev)](https://travis-ci.org/IBM-Cloud/insurance-bot) |
| [insurance-orders][orders_github_url] | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-orders.svg?branch=master)](https://travis-ci.org/IBM-Cloud/insurance-orders) | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-orders.svg?branch=dev)](https://travis-ci.org/IBM-Cloud/insurance-orders) |
| [insurance-catalog][catalog_github_url] | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-catalog.svg?branch=master)](https://travis-ci.org/IBM-Cloud/insurance-catalog) | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-catalog.svg?branch=dev)](https://travis-ci.org/IBM-Cloud/insurance-catalog) |
| [insurance-bot-dashboard][dashboard_github_url] | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-bot-dashboard.svg?branch=master)](https://travis-ci.org/IBM-Cloud/insurance-bot-dashboard) | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-bot-dashboard.svg?branch=dev)](https://travis-ci.org/IBM-Cloud/insurance-bot-dashboard) |
| [insurance-bot-ios][ios_github_url] | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-bot-ios.svg?branch=master)](https://travis-ci.org/IBM-Cloud/insurance-bot-ios) | - |
| [insurance-bot-android][android_github_url] | [![Build Status](https://travis-ci.org/IBM-Cloud/insurance-bot-android.svg?branch=master)](https://travis-ci.org/IBM-Cloud/insurance-bot-android) | - |

## Deploy

To deploy the full system all at once, check out the [Cloud Insurance Co. Toolchain][toolchain_github_url]

## Architecture

  ![Architecture Diagram](architecture.png)

  Visit the [wiki](https://github.com/IBM-Cloud/cloudco-insurance/wiki) for more details on Cloud Insurance Co. architecture and components.

## License

See [License.txt](License.txt) for license information.

# Privacy Notice

The application is configured to track deployments to [IBM Cloud](http://www.ibm.com/cloud-computing/Cloud/) and other Cloud Foundry platforms. Refer to the individual projects to understand what information is tracked and how to disable the tracking.

[bot_github_url]: https://github.com/IBM-Cloud/insurance-bot
[orders_github_url]: https://github.com/IBM-Cloud/insurance-orders
[catalog_github_url]: https://github.com/IBM-Cloud/insurance-catalog
[dashboard_github_url]: https://github.com/IBM-Cloud/insurance-bot-dashboard
[ios_github_url]: https://github.com/IBM-Cloud/insurance-bot-ios
[android_github_url]: https://github.com/IBM-Cloud/insurance-bot-android
[toolchain_github_url]: https://github.com/IBM-Cloud/insurance-toolchain
