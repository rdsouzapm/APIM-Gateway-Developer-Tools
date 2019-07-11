# Welcome to APIM-Gateway-Developer-Tools
#### Table of Contents
* [About the Beta Release](#about-the-beta-release)
* [Features](#features)
* [Known Limitations](#known-limitations)
* [Releases](#releases)
* [Reference Implementations](#reference-implementations)
* [Step By Step Installation Guide](#installation-guide)
* [Communication](#communication)
* [How You Can Contribute](#how-you-can-contribute)
* [License](#licenses)

This GitHub repository serves as a launchpad and sitemap for the CA API Gateway developer tools and CI/CD reference implementations for your organization to implement a CI/CD workflow for your Container Gateway solution development life cycle in ephemeral mode.

There are two main parts of the CI/CD workflow: local development (i.e., design time) and the actual CI/CD pipeline (i.e., run time) - it's important to distinguish the two as you'll be implementing the workflow in stages so that you can understand how the components work together. 

##Design Time: Road to CI/CD with GitOps-Oriented Local Development
Design Time refers to activities pertaining to the design or development activities of Gateway policy language.

##Run Time: CI/CD Pipeline with Log Analytics and Performance Metrics
Run Time refers to the activities pertaining to integration, delivery, and deployment activities of the Container Gateway life cycle – automation is used where the described tools allow it. The monitoring of logs and performance metrics are also included. 

## About the Beta Release
The Ephemeral Gateway is a work in progress and the contents of this Git repository is intended as a preview for any organization wanting to explore the implementation of a CI/CD workflow for their API Gateway solution development life cyle. We encourage you to give it a try and provide our development and testing teams your valuable feedback! 

### Features
For this first beta release, we've focused on the following features:
* GitHub repository set up for your GitOps workflow for design time and environment configuration
* Gateway Developer Tools to propagate the import, export, and build tasks for your policies and configurations
* Integration with industry-standard CI/CD tools such as Google Kubernetes Engine, Weave Flux, Jenkins, and Nexus

### Applicability and System Requirements
For a high-level overview of the CI/CD workflow and its core components, we highly recommend that you review the [reference architecture](https://github.com/CAAPIM/APIM-Gateway-Developer-Tools/wiki/Ephemeral-Gateway-Reference-Architecture) of the Ephemeral Gateway in the general Wiki.  

| Requirement | Supported/Tested in Beta Version |
| --- | --- |
| Gateway Form Factor(s) | Container Gateway Version 9.3 and newer |
| Container Orchestration Platform(s) | Google Kubernetes Engine Version 1.15 |
|Other Third Party Software | GitHub, Git, Golang, Jenkins, Weaveflux, Helm, Docker, Nexus - all latest versions as of June 2019 |

If you want to learn more about the benefits or an overview of the Ephemeral Gateway, check out our DocOps [documentation](https://docops.ca.com/ca-api-gateway/9-4/en/apis-and-toolkits/gateway-developer-plugin?src=contextnavpagetreemode).

## Known Limitations
See [Known Limitations](https://github.com/CAAPIM/APIM-Gateway-Developer-Tools/wiki/Known-Limitations) in the Wiki.

## Releases
The compiled release binaries can be found here: [Releases][Releases]

## Reference Implementations
A brief description about various repos for reference implmentation is described here 
[Respositories for Beta Release](https://github.com/CAAPIM/APIM-Gateway-Developer-Tools/wiki/Beta-Release-Repositories-and-Reference-Implementations)
We highly recommened you to go through this link to get used to various terms and repos used in this Beta release.


### Step By Step Installation Guide
To Test Beta release follow this step by step installation guide and set up various Design Time and Run Time components
[Step By Step Installation Guide](https://github.com/CAAPIM/APIM-Gateway-Developer-Tools/wiki/Step-by-Step-installation-Guide)

## Communication
- *Have general questions or need help?* Use [Stack Overflow][StackOverflow]. (Tag 'cagateway')
- *Find a bug?* Open an [issue][issues] with the steps to reproduce it.
- *Want to request a feature or have an idea?* Open an [issue][issues] to tell us.

## How You Can Contribute
Contributions are welcome and much appreciated. To learn more, see the [Contribution Guidelines][contributing].

## License
Copyright (c) 2019 CA. All rights reserved.

This software may be modified and distributed under the terms
of the MIT license. See the [LICENSE][license-link] file for details.

[StackOverflow]: http://stackoverflow.com/questions/tagged/cagateway
[issues]: https://github.com/CAAPIM/APIM-Gateway-Developer-Tools/issues
[releases]: ../../releases
[contributing]: /CONTRIBUTING.md
[license-link]: /LICENSE
