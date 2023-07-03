# Stock-Trading-App
Spring Boot Application Super Simple Stock Market
Built With
Maven - Dependency Management
JDK - Java™ Platform, Standard Edition Development Kit
Spring Boot - Framework to ease the bootstrapping and development of new Spring Applications
git - Free and Open-Source distributed version control system
Swagger - Open-Source software framework backed by a large ecosystem of tools that helps developers design, build, document, and consume RESTful Web services.
External Tools Used
Postman - API Development Environment (Testing Documentation)
To-Do
 Logger (Console, File, Mail)
 RESTful Web Service (CRUD)
 Swagger Documentation
 Junit Tests
 Integration Tests
Running the application locally
There are several ways to run Super Simple Stock Market on your local machine. One way is to execute the main method in the com.gbce.stock.market.StockMarketApplication class from your IDE.

Download the zip or clone the Git repository.
Unzip the zip file (if you downloaded one)
Open Command Prompt and Change directory (cd) to folder containing pom.xml
Open Eclipse
File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
Select the project
Choose the Spring Boot Application file (search for @SpringBootApplication)
Right Click on the file and Run as Java Application
Alternatively you can use the Spring Boot Maven plugin like so:

mvn spring-boot:run
URLs
URL	Method	Remarks
http://localhost:8080/gbce/trade/{stock-symbol}	POST	Custom Response Headers
http://localhost:8080/gbce/{stock-symbol}/dividend-yield	GET	
http://localhost:8080/gbce/{stock-symbol}/pe-ratio	GET	
http://localhost:8080/gbce/{stock-symbol}/volume-weight-price	GET	
http://localhost:8080/gbce/all-share-index	GET	
