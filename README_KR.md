# JBug Korea 2019
JBug Korea 2019 material for Quarkus presentation and demo

## Table of contents
 - [Prerequisites](#prerequisites): What you need before we start.
 - [Code Samples](#Samples): Session's sample code.

## Prerequisites
You will need to install the following if you want to run the examples

- [Java 1.8] (#https://adoptopenjdk.net) or later 
- [Maven] (#https://maven.apache.org) 3.5.3 or later
- [Graal](#https://www.graalvm.org) (used 1.0.0-rc-16-grl)


## Samples

Bootstrap your project

  mvn io.quarkus:quarkus-maven-plugin:0.16.1:create \
      -DprojectGroupId=org.acme \
      -DprojectArtifactId=getting-started \
      -DclassName="org.acme.quickstart.GreetingResource" \
      -Dpath="/hello"

-

