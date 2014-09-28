# build-tools #

![hazendaz](https://github.com/hazendaz/build-tools/blob/master/src/site/resources/images/hazendaz-banner.jpg)

## Quick Start ##

Configuration Tools for maven builds

Download this project and run `mvn clean install`.

Requires Maven 3.0.5 or better.

After running `mvn clean install` against this project, simply add the dependency to your pom for use with such
plugins as maven-java-formatter-plugin.

```
<dependency>
    <groupId>com.hazendaz</groupId>
    <artifactId>build-tools</artifactId>
    <version>1.0.1</version>
</dependency>
```

This project currently only contains information for maven-java-formatter-plugin to format using eclipse style formatter.

Site page is located [here](http://hazendaz.github.io/build-tools/)

## Introduction ##

This project is intended to be a helper jar for maven builds rather than deployments.  In the current iteration, it only
has eclipse code formatter xml to be used with maven-java-formatter-plugin to format code.

## Installation ##

Launching the build requires Maven install - everything will be downloaded upon build.

Type:

    mvn clean install

And add dependency to your pom.

```
<dependency>
    <groupId>com.hazendaz</groupId>
    <artifactId>build-tools</artifactId>
    <version>1.0.1</version>
</dependency>
```

Run `mvn clean install` against your own project and watch it format away.

## Notes ##

The POM is bigger than necessary to override super pom of eclipse so that it uses the latest versions.



