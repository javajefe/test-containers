Simple demo of [Testcontainers](https://www.testcontainers.org/) using together with [Spock framework](http://spockframework.org/).

### How to build and run
```
./gradlew test
```
It will
1. download proper version of Gradle
2. download all dependencies
3. compile the Spock-based test
4. download and run dockerized PostgreSql
5. run the test