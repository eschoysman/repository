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

### Utilities

#### Versioni disponibili:
- `0.1.0-SNAPSHOT` - LATEST


#### Dipendenze:
- **utility-core**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-core</artifactId>
    <version>${utilities-version}</version>
</dependency>
```
- **utility-math**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-math</artifactId>
    <version>${utilities-version}</version>
</dependency>
```
- **fluent**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>fluent</artifactId>
    <version>${utilities-version}</version>
</dependency>
```
- **utility-datastructures**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-datastructures</artifactId>
    <version>${utilities-version}</version>
</dependency>
```
- **utility-printer**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-printer</artifactId>
    <version>${utilities-version}</version>
</dependency>
```

### Utility

Dipendenza obsoleta, sostituita con le [utilities](#Utilities) sopra.
#### Versioni disponibili:
- `0.0.3-SNAPSHOT` - LATEST
- `0.0.2-SNAPSHOT`
- `0.0.1-SNAPSHOT`

```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>utility</artifactId>
        <version>LATEST</version>
    </dependency>
</dependencies>
```
