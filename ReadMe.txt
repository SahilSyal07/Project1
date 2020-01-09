Description 
========================================
This project is designed to take input body from user and return its response that is read from the properties file.

Gives a basic insight on how to set headers/body and NOT use hard-coded stuff in code.

Request Data can be anything. 

Request : - curl -XPOST --data '{"Print Details"}' http://localhost:9000/esb/project1
Response :- {"Name": "ESB_User1" , "Age":"25" , "ResponseMessage":"Hello World!!"}

### Additional Comments are added in the blueprint ###

========================================
To build this project use

    mvn install

To run the project you can execute the following Maven goal

    mvn camel:run
