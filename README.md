# Maven Multi Module Example

![Workflow Status](https://github.com/ncalteen/maven-multi-module-example/actions/workflows/01-java-ci-with-maven.yml/badge.svg)

This project is composed of a multi-module Maven project. GitHub Actions is
configured to build the project and upload the build artifacts for use in a
CI/CD pipeline.

The [01-java-ci-with-maven.yml](.github/workflows/01-java-ci-with-maven.yml)
workflow automatically caches dependencies that are downloaded during the build.
The current cache can be found in the
[Actions](https://github.com/ncalteen/maven-multi-module-example/actions/caches)
tab of the repository.
