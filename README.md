# Housekeeper Plugin

A jenkins plug-in that checks builds do not leave their junk lying around

Allows for customised checks to run before and after every build to ensure that shared resources are not leaked -- e.g. open ports or running services.

# Development Guide

## Plugin Tutorial
https://wiki.jenkins-ci.org/display/JENKINS/Plugin+tutorial

## Hosting Tutorial
https://wiki.jenkins-ci.org/display/JENKINS/Hosting+Plugins

## Readying for Eclipse development

  mvn -DdownloadSources=true -DdownloadJavadocs=true -DoutputDirectory=target/eclipse-classes eclipse:eclipse

