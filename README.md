# apache-ranger-release
Built from apache ranger release-2.0 on ubuntu.

This project is solely for someone who do not want to build ranger from scratch and save some time. 
please refer  https://github.com/apache/ranger for the rest of the detai;

command 
mvn clean compile package install assembly:assembly -Dmaven.test.skip=true -DskipJSTests -DskipTests -Drat.skip=true
