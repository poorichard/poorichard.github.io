---
layout: post
title: "Gradle Tips"
categories: trial
---

## What's gradle
 * build tool
 * combine Ant and Maven features
 * use Groovy for script language
 * under JVM

## Dependencies
Gradle use maven repositories, the dependencies is under repositories

```
repositories {
    mavenCentral()
}

dependencies {
    compile group: 'org.hibernate', name: 'hibernate-core', version: '3.6.7.Final'
    testCompile group: 'junit', name: 'junit', version: '4.+'
}
```

So, to search Packages , just use the maven search, like
http://mvnrepository.com/
or 
http://search.maven.org/
