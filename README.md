# KaiburrAssessment
This repository consists of the six tasks given by the Kaiburr. In the first task there is java rest api example.The second task contains the swagger codegen and so on.
--------------------Task 1: Java REST API Example---------------------

--------Technology Stack:----------

               Java
               Maven
            Spring Boot
              MongoDB

-------REST API Endpoints-----------

1. Add a Server

Endpoint: http://127.0.0.1:2017/addServer
Description: Adds a "server" object in JSON format to the server database.

2. Get Servers

Endpoint: http://127.0.0.1:2017/getServers
Description: Returns a list of "server" objects from the server database.

3. Get Server by ID

Endpoint: http://127.0.0.1:2017/getServers/{id}
Description: Returns a single "server" object that matches the provided ID.

4. Get Servers by Name

Description: Returns a list of "server" objects that match the provided name.

5. Delete Server by ID

Endpoint: http://127.0.0.1:2017/deleteServer/{id}
Description: Deletes a "server" object that matches the provided ID from the server database.

                ------------------Thank You!--------------------




------------------------Task 2: Swagger Codegen Implementation-------------------------

------------Integrating Swagger with Spring Boot and MongoDB---------------

In this task, we integrated Swagger into the existing project from Task 1. Here are the steps we followed:

Added Swagger Dependencies: We added the necessary dependencies for Swagger into the existing project.

Created SwaggerConfig.java: A new Java file named SwaggerConfig.java was created, and the class was annotated with @EnableSwagger2 to enable Swagger in the Spring Boot application.

Testing Swagger Locally: We tested Swagger on the local server using the URL http://127.0.0.1:2017/swagger-ui.html#. This provided us with a user-friendly UI for interacting with the API.
![Alt text](image-1.png)

Performing API Actions: We used the Swagger UI to perform various API actions, including adding a server.

Code Export: We exported the code generated from Swagger UI and tested it on an online editor.
By integrating Swagger, we provided an interactive API documentation and testing interface for the Spring Boot and MongoDB project, making it easier to develop, test, and document the APIs.

                                  -------------Thank you!---------------




# Task 1: Java REST API Example

## Technologies Used :
```
Java
Maven
SpringBoot
MongoDB
```
## Rest Api Endpoints
* Put a server ```http://127.0.0.1:2017/addServer``` Add "server" object in JSON form.

* GET servers ```http://127.0.0.1:2017/getServers``` Returns a list of "server" objects.

* GET server by id ```http://127.0.0.1:2017/getServers/{id}``` Returns a "server" object matching with id.

* GET servers by name ```http://127.0.0.1:2017/getServer/{name}``` Returns a list of "server" objects matching with name.

* DELETE server by id ```http://127.0.0.1:2017/deleteServer/{id}``` Deletes a "server" object matching with id. 





# Task 4 : WEB UI Forms

## Technologies Used
* Java
* SpringBoot
* Maven
* MongoDB
* Html
* CSS


## Below are the Steps to run the application

* ### First type ```http://localhost:2017/home``` to get home page with list of Servers.


* ### Click on ```Add Server``` button to add server. After Clicking on it new page will appear.



* ### List of Servers of after adding a server.


* ### Searching a server by id by clicking on ```Search Server By Id```.


* ### Output of search by id.



* ### Searching a server by name by clicking on ```Search Server By name```.



* ### Output of search by name.


* ### Deleting Server By Clicking on ```Delete Server``` and the delete server page will appear.



* ### Server List After Deleting.




## Thank you !!!


