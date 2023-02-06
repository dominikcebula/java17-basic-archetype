# Java17 Basic Aarchetype

## Intro

This repository contains a Maven Archetype that can be used to generate a Java 17 project.

Included example code will create a simple Java 17 Application:
```
Hello World!
```

## Usage

Invoke command:
```
mvn archetype:generate -DarchetypeGroupId=com.dominikcebula.archetypes -DarchetypeArtifactId=java17-basic-archetype
```

Maven Archetype will ask about `groupId`, `artifactId`, `version`, `package name` and will generate a project skeleton.

## Generated project

Having the project generated, invoke:
```
mvn clean install
```

Build output will be stored under `target` folder.

You can execute generated `jar` using command:
```
java -cp target/generated-output-1.0-SNAPSHOT.jar com.dominikcebula.Application
```
