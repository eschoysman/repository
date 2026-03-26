# Maven Repository

- [Definizione repository](#definizione-repository)
- [Dependencies](#dependencies)
    - [Utilities](#utilities)
        - utility-all
        - utility-core
        - utility-math
        - fluent
        - utility-datastructures
        - utility-file
        - utility-printer
    - [Mapper](#mapper)
    - [Simple State Machine](#simple-state-machine)
    - [RetrofitXtended](#retrofitxtended)
        - retrofitxtended-core
        - retrofitxtended-interceptors

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

### Utilities

#### Versioni disponibili per la libreria completa e per quelle specifiche:
- `0.1.0-SNAPSHOT` - LATEST

#### Libreria completa:
- **utility-all**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-all</artifactId>
    <version>LATEST</version>
</dependency>
```

<br>

#### Librerie specifiche:

- **utility-core**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-core</artifactId>
    <version>LATEST</version>
</dependency>
```

- **utility-math**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-math</artifactId>
    <version>LATEST</version>
</dependency>
```

- **fluent**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>fluent</artifactId>
    <version>LATEST</version>
</dependency>
```

- **utility-datastructures**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-datastructures</artifactId>
    <version>LATEST</version>
</dependency>
```

- **utility-file**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-file</artifactId>
    <version>LATEST</version>
</dependency>
```

- **utility-printer**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-printer</artifactId>
    <version>LATEST</version>
</dependency>
```

---
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
---
### Simple State Machine

```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>simple-state-machine</artifactId>
        <version>0.0.1-SNAPSHOT</version>
    </dependency>
</dependencies>
```
---
### RetrofitXtended
- `0.0.1-SNAPSHOT` - LATEST

Questa libreria necessità della dipendenza retrofitxtended-core per funzionare, la dipendenza retrofitxtended-interceptors auto-aggiunge degli inteterceptors utili

- **retrofitxtended-core**
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>retrofitxtended-core</artifactId>
        <version>LATEST</version>
    </dependency>
</dependencies>
```
- **retrofitxtended-interceptors**
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>retrofitxtended-interceptors</artifactId>
        <version>LATEST</version>
    </dependency>
</dependencies>
```
