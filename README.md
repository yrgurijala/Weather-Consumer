# Weather-Consumer
A Spring boot application that reads in objects from AWS SQS and loads that data into AWS RDS My SQL Database

Version 0.1
  - Designed the application using MVC architecture
  - Created a Weather Alert model to store data in a local database
  - Made it a RESTFul service
  - Controller accepts the data at http://localhost:8081/weatherAlert/addData

Version 0.2
  - Used AWS RDS MySQL database instead of local MySQL database

Version 1.0
  - Established Connection with AWS SQS Queue 
  - Listens to SQS for any new messages
  - Used Object Mapper to convert string to WeatherAlert java object
  - Deletes the message from SQS after its done processing
