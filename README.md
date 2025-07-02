# Jenkins for DevSecOps---- 

## Understanding the Usecase

The Repo  consists of two simple microservice.
 First one is NodeJs base, which is dockerized and run on port 5000,it has single endpoint "/plusone".

 The other microservice is SpringBoot base and it is run on prt 8080, it has single endpoint "/increment". Spring boot have other endpoint also like "/compare" and "/".

 when a user make a request on SpringBoot service with any number, its internally make an API call to NodeJS service and service increment a number and response back to the SpringBoot service.     
