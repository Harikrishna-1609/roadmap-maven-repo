# RoadMap ERP Automation Engine - Remote Maven Repository

This repository acts as the authoritative remote Maven repository for `com.roadmap:automation-engine`.

## How to use in your test project's `pom.xml`:

```xml
<repositories>
    <repository>
        <id>roadmap-maven-repo</id>
        <url>https://raw.githubusercontent.com/Harikrishna-1609/roadmap-maven-repo/main/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>com.roadmap</groupId>
        <artifactId>automation-engine</artifactId>
        <version>1.0.3</version>
    </dependency>
</dependencies>
```