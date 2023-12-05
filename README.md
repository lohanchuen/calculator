# Calculator

## Versions used to develop this application

**mvn --version**  Apache Maven 3.5.4

**java -version**  openjdk version "17.0.2" 2022-01-18

## To run the application:
Add the values to be added as arguments

Some examples:
```
mvn spring-boot:run -D'spring-boot.run.arguments="1,2,3"'

mvn spring-boot:run -D'spring-boot.run.arguments="1\n2,3"'

mvn spring-boot:run -D'spring-boot.run.arguments="//;\n1;2"'

mvn spring-boot:run -D'spring-boot.run.arguments="//[|][%]\n1|2%3"'

mvn spring-boot:run -D'spring-boot.run.arguments="//[|][%]\n1||||||2%%%%%%3"'
```
