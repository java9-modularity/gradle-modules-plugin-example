# Example project using the Gradle Modules Plugin

This is a small multi module example project that uses the [Gradle Modules Plugin](https://github.com/java9-modularity/gradle-modules-plugin).
It demonstrates the folling:

* Building a project with multiple modules (all modules have a `module-info.java`
* Running blackbox module tests (the `greeter.provider.test`)
* Services (`greeter.provider`)
* Using the `application` plugin to run from Gradle, and build distributions. (See `build.gradle` in the `greeter.runner` module)

