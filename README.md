# maven-releases

This repository contains versions for Android libraries using Maven.

# How to include in project

```groovy

subprojects {
    repositories {
        maven { url "https://raw.github.com/laenger/maven-releases/master/releases" }
    }
}

```

Reference the repository from this location using:

```groovy
dependencies {
    compile "biz.laenger.android:{libraryname}:{version}"
}
```