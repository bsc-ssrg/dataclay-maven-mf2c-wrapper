# dataclay-maven-mf2c-wrapper

To include dataClay Mf2c wrapper as a dependency in a maven project, add the following repository and dependency to the `pom.xml`:

```xml
<repository>
    <id>DataClay Mf2c Wrapper repository</id>
    <url>https://raw.github.com/bsc-ssrg/dataclay-maven-mf2c-wrapper/repository</url>
</repository>
```

```xml
<dependency>
    <groupId>dataclay.mf2c</groupId>
    <artifactId>wrapper</artifactId>
    <version>trunk</version>
</dependency>
<dependency>
	<groupId>dataclay.mf2c</groupId>
	<artifactId>stubs</artifactId>
	<version>trunk</version>
</dependency>
```
