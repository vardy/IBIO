# IBIO

[![Version](https://jitpack.io/v/vardy/IBIO.svg)](https://jitpack.io/#vardy/IBIO)
[![Downloads](https://img.shields.io/jitpack/dm/github/vardy/IBIO?label=Maven%20Downloads)](https://github.com/vardy/IBIO)
[![License](https://img.shields.io/github/license/vardy/IBIO?label=License)](https://github.com/vardy/IBIO/blob/master/LICENSE) 

## Overview

This class provides a simplified interface between
simple Java process for input and output and the methods
defined in the IB's JETS standard for the Option C (OOP)
examination.

## Installation

**🔵 Without Maven/Gradle**

1) Go [here](https://github.com/vardy/IBIO/blob/master/IBIO.jar) and click 'download' to get IBIO
2) In your IDE (code editor), go to your project settings ('Project Structure' in IntelliJ)
3) Find the option to install a library/dependency/jar
4) Once prompted, select the IBIO jar file you downloaded in step 1

**🔵 Maven**

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

**🔵 Gradle**

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

Import for use in a class:    
```java
import dev.vardy.IBIO;
```

Example method calls:
```java
IBIO.output("Hello, world");
IBIO.input("What is your favourite colour?");
```

JETS specification with usage of IBIO:    
https://ib.compscihub.net/wp-content/uploads/2015/04/JETS-Java-rules1.pdf