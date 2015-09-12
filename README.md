pom-osgi
========

Base POM for OSGI http://www.fuin.org/ projects

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.fuin/pom-osgi/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.fuin/pom-osgi/)

###Snapshots

Snapshots can be found on the [OSS Sonatype Snapshots Repository](http://oss.sonatype.org/content/repositories/snapshots/org/fuin "Snapshot Repository"). 

Add the following to your .m2/settings.xml to enable snapshots in your Maven build:

```xml
<repository>
    <id>sonatype.oss.snapshots</id>
    <name>Sonatype OSS Snapshot Repository</name>
    <url>http://oss.sonatype.org/content/repositories/snapshots</url>
    <releases>
        <enabled>false</enabled>
    </releases>
    <snapshots>
        <enabled>true</enabled>
    </snapshots>
</repository>
```
