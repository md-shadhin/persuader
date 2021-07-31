## Installation

1. In your **project-level** `build.gradle` file, add this plugin as a buildscript dependency.

```groovy
buildscript {
  repositories {
    // Check that you have Maven Central repository (if not, add it).
    mavenCentral()
  }

  dependencies {
    classpath 'io.github.shadhinkhan:persuades-ray-bhai:1.0.0'
  }
}
```

2. In your **app-level** `build.gradle` file, apply the plugin:
```groovy
apply plugin: 'persuades-ray-bhai'

//or
plugins {
  id 'persuades-ray-bhai'
}
```
