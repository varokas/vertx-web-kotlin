# Vertx-Web-Kotlin
Create a simple reactive web server with [Vert.X](https://vertx.io/) using kotlin

## Prerequisites
* Java 1.8+

## Developing

Import to intellij
```
idea .
```

## Running 

Run with class reloading when file changed
```
./gradlew run
```

Then go to http://localhost:8080

## Deploying
```
./gradlew stage  # Package all jars into one jar
java -jar ./
```

## Reference
* https://vertx.io/docs/vertx-web/kotlin/
* https://github.com/vert-x3/vertx-examples/tree/master/kotlin-examples/web
