# Jenkins Mock Load Builder Plugin

This plugin provides a build step that generates mock load on the build node for use when testing Jenkins scalability.

# Environment

The following build environment is required to build this plugin

* `java-1.6` and `maven-3.0.5`

# Build

To build the plugin locally:

    mvn clean verify

# Release

To release the plugin:

    mvn release:prepare release:perform -B

# Test local instance

To test in a local Jenkins instance

    mvn hpi:run

  [wiki]: http://wiki.jenkins-ci.org/display/JENKINS/Random+Job+Builder+Plugin
