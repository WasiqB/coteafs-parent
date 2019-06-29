# coteafs-parent

## What is it all about?

This is Maven parent project containing all common Maven configurations, plugins, properties, etc. which is used by other modules in coteafs suite of projects.

## Why created this project?

It is not advisable to copy paste same block of common code in every project's `pom.xml`. To solve this problem, a common parent asset was decided to be created. This project can be used by anyone who is looking out to use following plugins in their POM.

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

## Usage

In your `pom.xml`, add following block to use this POM,

```xml
  . . .
  <parent>
    <groupId>com.github.wasiqb.coteafs</groupId>
    <artifactId>parent</artifactId>
    <version>2.2.0</version>
  </parent>
  . . .
```
