# EventTrackerRepo

Pre Assumption
File name will always be logfile.txt

Used in-memory HSQLDB

Command to build application
mvn clean install

Commands to run application from target folder
cd target
java -jar eventTracker-0.0.1-SNAPSHOT.jar filePathLocation
eg. if filePathLocation is C:/Users/cshrivas/FileReader
    java -jar eventTracker-1.0.-SNAPSHOT.jar C:/Users/cshrivas/FileReader 

Command to run application in debug mode
java -jar eventTracker-0.0.1-SNAPSHOT.jar filePathLocation --logging.level.org.springframework=DEBUG --logging.level.com.cs.tracker.logStack=DEBUG
