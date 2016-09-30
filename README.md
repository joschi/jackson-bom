# Jackson Bill Of Materials (BOM)

[![Build Status](https://travis-ci.org/joschi/jackson-bom.svg?branch=master)](https://travis-ci.org/joschi/jackson-bom)

This project is an unofficial bill of materials (BOM) for the [Jackson](http://wiki.fasterxml.com/JacksonHome) project.


## Usage

### Maven

Simply import the `jackson-bom` artifact into your project's `<dependencyManagement>` section:

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.github.joschi.jackson</groupId>
            <artifactId>jackson-bom</artifactId>
            <version>${jackson.version}</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```

### Gradle

TODO


## License

Copyright (c) 2016 Jochen Schalanda

This library is licensed under the Apache License, Version 2.0.

See http://www.apache.org/licenses/LICENSE-2.0.html or the [LICENSE](LICENSE) file in this repository for the full license text.
