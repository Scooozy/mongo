MongoDB Workshop : Java Services
=================================

This part of the project contains a Web application, powered by Jetty, that expose the Comics data using a REST API.


During the build process the AngujarJS UI is copied in to the target folder.


### Requirements:

1. Java 8 or later
2. Maven 3
3. MongoDB 4.0.x



## Build / Run

Build:
`mvn clean package`

Run:
`mvn exec:java -Dexec.mainClass="org.mongodb.workshop.Main" `



### Build and refresh repository

`mvn clean install dependency:go-offline -Dmaven.repo.local=repository -Pdev`


Note: [All Data provided by Marvel. © 2014 MARVEL](http://marvel.com)
