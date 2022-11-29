# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11

# Screenshots

# CI

## GitHub action config: gradle.yml

![Screenshot](./DOC/Images/1.1.png "")

## GitHub CI action running

![Screenshot](./DOC/Images/1.2.png "")

![Screenshot](./DOC/Images/1.3.png "")

![Screenshot](./DOC/Images/1.4.png "")

![Screenshot](./DOC/Images/1.5.png "")

# CD

## Create cluster

![Screenshot](./DOC/Images/2.1.png "")

## Enable APIs

![Screenshot](./DOC/Images/2.2.png "")

![Screenshot](./DOC/Images/2.3.png "")

## Project ID

![Screenshot](./DOC/Images/2.4.png "")

## Create service account

![Screenshot](./DOC/Images/2.5.png "")

## Grant accesses

![Screenshot](./DOC/Images/2.6.png "")

![Screenshot](./DOC/Images/2.7.png "")

## Create private key

![Screenshot](./DOC/Images/2.8.png "")

![Screenshot](./DOC/Images/2.9.png "")

## Create GitHub Secrets

![Screenshot](./DOC/Images/2.10.png "")

![Screenshot](./DOC/Images/2.11.png "")

![Screenshot](./DOC/Images/2.12.png "")

![Screenshot](./DOC/Images/2.13.png "")

## GitHub action config: google.yml

![Screenshot](./DOC/Images/2.14.png "")

## kustomization.yml

![Screenshot](./DOC/Images/2.15.png "")

## service.yml

![Screenshot](./DOC/Images/2.16.png "")

## deployment.yml

![Screenshot](./DOC/Images/2.17.png "")

## Create GitHub release

![Screenshot](./DOC/Images/2.18.png "")

![Screenshot](./DOC/Images/2.19.png "")

## GitHub CD action running

![Screenshot](./DOC/Images/2.20.png "")

![Screenshot](./DOC/Images/2.21.png "")

## Deployed workload

![Screenshot](./DOC/Images/2.22.png "")

## Deployed service

![Screenshot](./DOC/Images/2.23.png "")

## Create Ingress

![Screenshot](./DOC/Images/2.24.png "")

![Screenshot](./DOC/Images/2.25.png "")

## Visit frontend

![Screenshot](./DOC/Images/2.26.png "")