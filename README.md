# IBIO

## Overview

This class provides a simplified interface between
simple Java process for input and output and the methods
defined in the IB's JETS standard for the Option C (OOP)
examination.

## Installation

**Without Maven/Gradle**

**Maven**

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
    <groupId>com.github.vardy</groupId>
    <artifactId>IBIO</artifactId>
    <version>1.0</version>
</dependency>
```

**Gradle**

```gradle
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}

dependencies {
    implementation 'com.github.vardy:IBIO:1.0'
}
```

## Usage