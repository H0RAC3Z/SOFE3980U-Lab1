Build with site
```
mvn clean package site assembly:single
```
Build without site
```
mvn clean package assembly:single
```
Run jar
```
java -jar target/BinaryCalculator-1.0.0-jar-with-dependencies.jar
```
Open site from root of repo, use browser of your choice
```
brave BinaryCalculator/target/site/index.html
```
