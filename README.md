# APIM-Gateway-Developer-Tools
Get started with APIM Gateway Developer Tools and CI/CD Reference Implementations

## Get Started
Check out our [documentation][documentation] for sample code, video tutorials, and more.  

## Gateway Developer Tools Framework
The Android Mobile SDK consists of these frameworks:

- [APIM-Gateway-Developer-Tools](https://github.com/CAAPIM/APIM-Gateway-Developer-Tools)
- [gateway-developer-plugin](https://github.com/CAAPIM/gateway-developer-plugin)
- [gateway-developer-example](https://github.com/CAAPIM/gateway-developer-example)
- [gateway-developer-skeleton-repo](https://github.com/CAAPIM/gateway-developer-skeleton-repo)
- [gateway-export-plugin](https://github.com/CAAPIM/gateway-export-plugin)
- [example-environment-configuration-repo](https://github.com/CAAPIM/example-environment-configuration-repo)
- [gateway-developer-multimodule-skeleton-repo](https://github.com/CAAPIM/gateway-developer-multimodule-skeleton-repo)
- [gateway-metrics-grafana-example](https://github.com/CAAPIM/gateway-metrics-grafana-example)
- [gateway-tic-tac-toe](https://github.com/CAAPIM/gateway-tic-tac-toe)
- [template-policies](https://github.com/CAAPIM/template-policies)

For more information about our mobile products see the [developer website][mas.ca.com].

## Features

* **Secure API Calls** - Protect APIs with Mutual TLS and control API access on application, user and device level.
* **Authentication** - Implement authentication with username/password, Facebook, Google, Twitter sign-in.
* **Second Factor Auth** - Secure critical APIs with One Time Password.
* **Single Sign-On** - Share user credentials between your apps.
* **Enterprise Browser** - Extend the single sign-on session to web applications.
* **Proximity Login** - Transfer the user session between devices and platforms.
* **Fingerprint Sessions Lock** - Support phone unlocking using fingerprint recognition.
* **Messaging** - Create collaborative apps with secure, reliable messaging.
* **User Management** - Seamlessly integrate your app with an existing enterprise user directory.
* **Private Cloud Storage** - Store data in a private cloud and access it from all of your devices.
* **Pub/Sub** - Create real-time, IoT-friendly apps using an MQTT-based Pub/Sub infrastructure.
* **Adhoc Groups** - Create groups on-the-fly for collaborative apps.
* **Local Storage** - Store data on devices with enterprise-grade encryption.
* **UI Template** - Provides resources to implement a user login dialog, Social Login, One-Time Password, and Proximity Login (QR code and BLE), to save time during UI creation and app prototyping.

## Installation
Edit your build.gradle file and add below dependency:
```gradle
    dependencies {
        implementation 'com.ca:mas-foundation:1.8.00'

        implementation 'com.ca:mas-connecta:1.8.00' // (Optional) Only required when using mas connecta
        implementation 'com.ca:mas-storage:1.8.00' // (Optional) Only required when using mas storage
        implementation 'com.ca:mas-identity-management:1.8.00' // (Optional) Only required when using mas identity management
        implementation 'com.ca:masui:1.8.00' // (Optional) Only required when using MASUI Template. The MAS UI library provides sample user interfaces for Login, OTP, Social Login, and Enterprise Browser.

        implementation 'org.bouncycastle:bcpkix-jdk15on:1.55' // (Optional) Only required when you want to support Android 4.1.x
    }
```
## SDK Releases
The compiled release binaries can be found here: [Releases][Releases]

## Sample Apps
**All sample apps have moved to GITHub as of 1.6.00 release. Links will redirect to the latest released versions.**

- [gateway-developer-skeleton-repo](https://github.com/CAAPIM/gateway-developer-skeleton-repo)
- [gateway-developer-multimodule-skeleton-repo](https://github.com/CAAPIM/gateway-developer-multimodule-skeleton-repo)
- [gateway-metrics-grafana-example](https://github.com/CAAPIM/gateway-metrics-grafana-example)
- [gateway-tic-tac-toe](https://github.com/CAAPIM/gateway-tic-tac-toe)
- [template-policies](https://github.com/CAAPIM/template-policies)

## Communication
- *Have general questions or need help?*, use [Stack Overflow][StackOverflow]. (Tag 'massdk')
- *Find a bug?*, open an [issue][issues] with the steps to reproduce it.
- *Request a feature or have an idea?*, open an [issue][issues].

## How You Can Contribute
Contributions are welcome and much appreciated. To learn more, see the [Contribution Guidelines][contributing].

## Documentation
For more documentation including API references, go to our [main website][docs].

## License
Copyright (c) 2017 CA. All rights reserved.

This software may be modified and distributed under the terms
of the MIT license. See the [LICENSE][license-link] file for details.

[mag]: https://docops.ca.com/mag
[mas.ca.com]: http://mas.ca.com/
[docs]: http://mas.ca.com/docs/
[blog]: http://mas.ca.com/blog/
[get-started]: http://mas.ca.com/get-started
[StackOverflow]: http://stackoverflow.com/questions/tagged/massdk
[issues]: https://github.com/CAAPIM/Android-MAS-SDK/issues
[releases]: ../../releases
[contributing]: /CONTRIBUTING.md
[license-link]: /LICENSE
[video]: https://www.ca.com/us/developers/mas/videos.html
[documentation]: https://www.ca.com/us/developers/mas/docs.html
