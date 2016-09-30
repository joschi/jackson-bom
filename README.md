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

Also see [Introduction to the Dependency Mechanism - Importing Dependencies](https://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html#Importing_Dependencies).

### Gradle

Gradle doesn't support Maven BOMs out of the box, but there are a few 3rd party plugins addressing this issue:

* [Nebula Dependency Recommender](https://github.com/nebula-plugins/nebula-dependency-recommender-plugin#readme)
* [Spring Dependency management plugin](https://github.com/spring-gradle-plugins/dependency-management-plugin#readme)


## License

Copyright (c) 2016 Jochen Schalanda

This library is licensed under the Apache License, Version 2.0.

See http://www.apache.org/licenses/LICENSE-2.0.html or the [LICENSE](LICENSE) file in this repository for the full license text.
