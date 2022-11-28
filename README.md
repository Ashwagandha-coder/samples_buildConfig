# Sample BuildConfig

This project was created for samples - (Gradle DSL, BuildConfig)

### Base install code in buildSrc

```Gradle

import org.gradle.kotlin.dsl.`kotlin-dsl`

plugins {
    `kotlin-dsl`
}

repositories {
    mavenCentral()
}

```