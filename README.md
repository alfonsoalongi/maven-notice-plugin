# maven-notice-plugin

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jasig.maven/maven-notice-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.jasig.maven/maven-notice-plugin)
[![Build Status](https://travis-ci.org/Jasig/maven-notice-plugin.svg?branch=master)](https://travis-ci.org/Jasig/maven-notice-plugin)

Generates NOTICE files based on a given template. Defaults to Apereo copyright.

```xml
<plugin>
  <groupId>org.jasig.maven</groupId>
  <artifactId>maven-notice-plugin</artifactId>
    <version>1.1.0</version>
    <configuration>
        <noticeTemplate>${jasig-notice-template-url}</noticeTemplate>
        <licenseMapping>
            <param>${jasig-license-lookup-url}</param>
        </licenseMapping>
    </configuration>
</plugin>
```
