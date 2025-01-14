# Data Product Hub Java SDK Version 0.2.0

Java client library to interact with various Data Product Hub Service APIs.

Disclaimer: this SDK is being released initially as a **pre-release** version.
Changes might occur which impact applications that use this SDK.

## Table of Contents

<!--
  The TOC below is generated using the `markdown-toc` node package.

      https://github.com/jonschlinkert/markdown-toc

  You should regenerate the TOC after making changes to this file.

      npx markdown-toc --maxdepth 4 -i README.md
  -->

<!-- toc -->

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Maven](#maven)
  - [Gradle](#gradle)
- [Using the SDK](#using-the-sdk)
- [Questions](#questions)
- [Issues](#issues)
- [Open source @ IBM](#open-source--ibm)
- [Contributing](#contributing)
- [License](#license)

<!-- tocstop -->

## Overview

The IBM Cloud Data Product Hub Java SDK allows developers to programmatically interact with the following services:

| Service Name                                                   | Artifact Coordinates    |
| -------------------------------------------------------------- | ----------------------- |
| [Data Product Hub](https://cloud.ibm.com/apidocs/dataproducts) | com.ibm.cloud:dph:0.2.0 |

## Prerequisites

[ibm-cloud-onboarding]: https://cloud.ibm.com/registration

- An [IBM Cloud][ibm-cloud-onboarding] account.
- An IAM API key to allow the SDK to access your account. Create one [here](https://cloud.ibm.com/iam/apikeys).
- Java 8 or above.

## Installation

The current version of this SDK is: 0.2.0

The project artifacts are published on the public [Maven Central](https://repo1.maven.org/maven2/)
artifact repository. This is the default public repository used by maven when searching for dependencies.
To use this repository within a gradle build, please see
[this link](https://docs.gradle.org/current/userguide/declaring_repositories.html).

To use a particular service, define a dependency that contains the
artifact coordinates (group id, artifact id and version) for the service.
Here are examples for maven and gradle:

### Maven

```xml
<dependency>
    <groupId>com.ibm.cloud</groupId>
    <artifactId>dph</artifactId>
    <version>0.2.0</version>
</dependency>
```

### Gradle

```gradle
compile 'com.ibm.cloud:dph:0.2.0'
```

## Using the SDK

For general SDK usage information, please see [this link](https://github.com/IBM/ibm-cloud-sdk-common/blob/main/README.md)

## Questions

If you are having difficulties using this SDK or have a question about the IBM Cloud services,
please ask a question at
[Stack Overflow](http://stackoverflow.com/questions/ask?tags=ibm-cloud).

## Issues

If you encounter an issue with the project, you are welcome to submit a
[bug report](<github-repo-url>/issues).
Before that, please search for similar issues. It's possible that someone has already reported the problem.

## Open source @ IBM

Find more open source projects on the [IBM Github Page](http://ibm.github.io/)

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md).

## License

The IBM Cloud MySDK Java SDK is released under the Apache 2.0 license.
The license's full text can be found in [LICENSE](LICENSE).
