# Sample Clojure webapp running on clever-cloud

## Why?

I did not find an official support of Clojure on the clever-cloud docs, but since Clojure runs on Java, one way to
do it is to build locally using `lein uberjar`, push that standalone jar on the repo
and use the [JAR deployement support of clever-cloud](https://www.clever-cloud.com/doc/java/java-jar/).

## Prerequisites

You will need Java and Leiningen installed.

## Build

    lein uberjar
    git add -f target/app-0.1.0-SNAPSHOT-standalone.jar
    git push


