Java 11 + JUnit 5 Quickstart Maven Archetype
======================================

This is an updated version of the original project from https://github.com/thiagoprocaci/java8-junit5-archetype

Summary
-------
The project is a Maven archetype for Java 8 and JUnit 5


Prerequisites
-------------

- JDK 11
- Maven 3


Install archetype locally
-------------------------

To install the archetype in your local repository execute the following commands:

```bash
    git clone https://github.com/arshadm/java11-junit5-archetype.git
    cd java11-junit5-archetype
    mvn clean install
```


Last step: creating a project
----------------

```bash
 mvn archetype:generate \
 -DarchetypeGroupId=com.arshadm \
 -DarchetypeArtifactId=java11-junit5-archetype \
 -DarchetypeVersion=1.0-SNAPSHOT  \
 -DgroupId=com.example       \
 -DartifactId=my-project      \
 -DinteractiveMode=false
```
