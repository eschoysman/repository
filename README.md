# Maven Repository

## Definizione repository

```xml
<repositories>
    <repository>
        <id>repository-mvn-repo</id>
        <url>https://raw.github.com/eschoysman/repository/mvn-repo/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```

## Dependencies

### Mapper

```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>mapper</artifactId>
        <version>1.0.0</version>
    </dependency>
</dependencies>
```

Versioni disponibili: 

- 1.0.0

### Utility

```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>utility</artifactId>
        <version>0.0.3-SNAPSHOT</version>
    </dependency>
</dependencies>
```

Versioni disponibili: 

- 0.0.3-SNAPSHOT
- 0.0.2-SNAPSHOT
- 0.0.1-SNAPSHOT

### **Simple State Machine**

```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>simple-state-machine</artifactId>
        <version>0.0.1-SNAPSHOT</version>
    </dependency>
</dependencies>
```

Versioni disponibili: 

- 0.0.1-SNAPSHOT
