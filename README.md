# coteafs-parent

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)][home]
[![Maven Central](https://img.shields.io/maven-central/v/com.github.wasiqb.coteafs/parent.svg)][maven]
[![Github Releases](https://img.shields.io/github/downloads/WasiqB/coteafs-parent/total.svg)](https://github.com/WasiqB/coteafs-parent/releases)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## :boom: What is it all about?

This is Maven parent project containing all common maven configurations, dependencies, plugins and properties, which is used by other modules in coteafs suite of projects.

## :golf: Why was this project created?

It was a tedious task of copy pasting same block of common code in every project's `pom.xml`. To solve this problem, a common parent asset was created. This project can be used by anyone who is looking out to use following plugins in their POM:

### Plugins used

:point_right: `maven-clean-plugin`

:point_right: `maven-resources-plugin`

:point_right: `maven-compiler-plugin`

:point_right: `maven-source-plugin`

:point_right: `maven-javadoc-plugin`

:point_right: `versions-maven-plugin`

:point_right: `maven-surefire-plugin`

:point_right: `jacoco-maven-plugin`

:point_right: `maven-surefire-plugin`

### Profiles declared

:point_right: `coverage-per-test`: Used for analyzing code coverage for Sonarcloud.

:point_right: `release`: Releases artifacts to Maven central.

## :pushpin: Usage?

You can use the following dependency into your `pom.xml` to use this library.

```xml
  . . .
  <parent>
    <groupId>com.github.wasiqb.coteafs</groupId>
    <artifactId>parent</artifactId>
    <version>2.2.0</version>
  </parent>
  . . .
```
## :question: Need Assistance?
* Directly chat with me on my [site][] and I'll revert to you as soon as possible.
* Discuss your queries by writing to me @ wasbhamla2005@gmail.com
* If you find any issue which is bottleneck for you, [search the issue tracker][] to see if it is already raised.
* If not raised, then you can create a [new issue][] with required details as mentioned in the issue template.

## :star: What you do if you like the project?
* Spread the word with your network.
* **Star** the project to make the project popular.
* Stay updated with the project progress by **Watching** it.
* Contribute to fix open issues, documentations or add new features. To know more, see our [contributing][] page.
* I would be delighted if you can **Sponsor** this project and provide your support to open source development by clicking on the **Sponsor button** on the top of this repository.

## :heavy_check_mark: Contributors

<div>
  <ul>
    <li>
      <a href="https://github.com/WasiqB">
        <img alt="Wasiq Bhamla: Framework developer and maintainer." src="https://github.com/WasiqB.png" width=100 height=100 />
      </a>
    </li>
    <li>
      <a href="https://github.com/mfaisalkhatri">
        <img alt="Mohammad Faisal Khatri: Framework Tester." src="https://github.com/mfaisalkhatri.png" width=100 height=100 />
      </a>
    </li>
  </ul>
</div>

## :ticket: Versioning ideology

<p align="left">
  <a href="http://semver.org/">
    <img src="assets/semver.png" width=300 />
  </a>
</p>

## :copyright:Wasiq Bhamla

<p align="left">
  <a href="http://www.apache.org/licenses/LICENSE-2.0">
    <img src="http://www.apache.org/img/asf_logo.png" width=300 />
  </a>
</p>

[site]: https://wasiqb.github.io
[search the issue tracker]: https://github.com/WasiqB/coteafs-parent/issues?q=something
[new issue]: https://github.com/WasiqB/coteafs-parent/issues/new
[contributing]: .github/CONTRIBUTING.md
[home]: https://github.com/wasiqb/coteafs-parent
[maven]: https://maven-badges.herokuapp.com/maven-central/com.github.wasiqb.coteafs/parent