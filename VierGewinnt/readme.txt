mvn -DskipTests jfx:jar
mvn -DskipTesta jfx:run
mvn clean
mvn -DskipTests install
mvn sonar:sonar
