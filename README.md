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
        - retrofitxtended-single
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
- Versione
```xml
<properties>
  <utility.version>0.1.0-SNAPSHOT</utility.version>
</properties>
```

#### Libreria completa:
- **utility-all**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-all</artifactId>
    <version>${utility.version}</version>
</dependency>
```

#### Librerie specifiche:

- **utility-core**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-core</artifactId>
    <version>${utility.version}</version>
</dependency>
```

- **utility-math**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-math</artifactId>
    <version>${utility.version}</version>
</dependency>
```

- **fluent**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>fluent</artifactId>
    <version>${utility.version}</version>
</dependency>
```

- **utility-datastructures**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-datastructures</artifactId>
    <version>${utility.version}</version>
</dependency>
```

- **utility-file**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-file</artifactId>
    <version>${utility.version}</version>
</dependency>
```

- **utility-printer**
```xml
<dependency>
    <groupId>it.eschoysman</groupId>
    <artifactId>utility-printer</artifactId>
    <version>${utility.version}</version>
</dependency>
```

---
### Mapper
- Versione
```xml
<properties>
  <mapper.version>1.0.0</mapper.version>
</properties>
```
- Dipendenza
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>mapper</artifactId>
        <version>${mapper.version}</version>
    </dependency>
</dependencies>
```
---
### Simple State Machine
- Versione
```xml
<properties>
  <simple-state-machine.version>0.0.1-SNAPSHOT</simple-state-machine.version>
</properties>
```
- Dipendenza
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>simple-state-machine</artifactId>
        <version>${simple-state-machine.version}</version>
    </dependency>
</dependencies>
```
---
### RetrofitXtended
- Versione
```xml
<properties>
  <retrofitxtended.version>0.0.1-SNAPSHOT</retrofitxtended.version>
</properties>
```

#### Fat Jar
Versione completa della libreria con tutte le sue dipendenze integrate, no javadoc.

- Dipendenza
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>retrofitxtended-single</artifactId>
        <version>${retrofitxtended.version}</version>
    </dependency>
</dependencies>
```


#### Versione leggera
Versione leggera della libreria, senza le dipendenze integrate, con javadoc.

Questa versione necessità della dipendenza retrofitxtended-core per funzionare. La dipendenza retrofitxtended-interceptors auto-aggiunge degli inteterceptors utili:

- **retrofitxtended-core**
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>retrofitxtended-core</artifactId>
        <version>${retrofitxtended.version}</version>
    </dependency>
</dependencies>
```

- **retrofitxtended-interceptors**
```xml
<dependencies>
    <dependency>
        <groupId>it.eschoysman</groupId>
        <artifactId>retrofitxtended-interceptors</artifactId>
        <version>${retrofitxtended.version}</version>
    </dependency>
</dependencies>
```
