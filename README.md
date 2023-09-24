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

## Testing APIs on POSTMAN

ScreenShots

* ##### Adding Server 
![AddingServer](https://user-images.githubusercontent.com/73234020/158126625-4acafd28-6b27-4000-af10-991f793cb986.png)

* ##### Get Servers : Here we get all the servers present in database.

![GetServers](https://user-images.githubusercontent.com/73234020/158126948-5c6da388-dfda-47ce-84d1-5e65168df338.png)

* ##### Get Server By Id : Here we get only one server for the given id and if there is no server for given id then we get status as ``` 404 NOT FOUND ```.
Get Server By Id
![GetServerById](https://user-images.githubusercontent.com/73234020/158127198-03a097dc-2d2d-4753-ae83-adc39ea20a40.png)

```404 NOT FOUND```
![GetServersById(404 not found)](https://user-images.githubusercontent.com/73234020/158127233-eeb4881d-e29b-42e3-8d8c-8119f9051b59.jpg)

* ##### Get Server By Name : Here we get all servers by name and if there is no server then we get ```404 NOT FOUND```. 

![GetServerByName](https://user-images.githubusercontent.com/73234020/158127958-034116db-7f1d-438f-91f0-19774a2be5f9.png)

```404 NOT FOUND```
![GetServersByName(404 not found)](https://user-images.githubusercontent.com/73234020/158128985-4be3b264-7f4c-4f48-8c3f-e891b0f71077.png)


* ##### Delete Server : Here the server gets deleted for a given id.
![DeleteServer](https://user-images.githubusercontent.com/73234020/158128248-bf5a1522-0f02-4961-939c-7a7e007ba737.png)

* #### MongoDB database 
![MongoDBDatabase](https://user-images.githubusercontent.com/73234020/158129122-cdf80e34-fe71-4d7f-b23c-173d0aa4ca86.png)


## Thank You !!!


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

![ServersList](https://user-images.githubusercontent.com/73234020/158184894-ad4ca136-a461-4e26-a437-bcc6f8c10136.png)

* ### Click on ```Add Server``` button to add server. After Clicking on it new page will appear.

![AddingServer](https://user-images.githubusercontent.com/73234020/158185214-aed50155-27cc-4c81-a171-dc8c7242f083.png)

* ### List of Servers of after adding a server.

![ServerListAfterAdding](https://user-images.githubusercontent.com/73234020/158185385-11e9fd10-d35d-418a-8a61-2e727a14094e.png)

* ### Searching a server by id by clicking on ```Search Server By Id```.
 
 ![getServerByIdOutput](https://user-images.githubusercontent.com/73234020/158185810-f56eee62-9198-4d7f-9452-4f2401f83f66.png)

* ### Output of search by id.

![getServerByIdOutput](https://user-images.githubusercontent.com/73234020/158185970-5e3bcde0-7592-42e4-80cc-1c24b1539ae4.png)

* ### Searching a server by name by clicking on ```Search Server By name```.

![GetServerByName](https://user-images.githubusercontent.com/73234020/158186078-088493d3-e04c-4ff6-8f83-b4cfda1b6409.png)

* ### Output of search by name.

![GetServerByNameOutput](https://user-images.githubusercontent.com/73234020/158186161-fa73da24-b72e-4ee6-bbc0-794ca3df2b11.png)

* ### Deleting Server By Clicking on ```Delete Server``` and the delete server page will appear.

![deleteServer](https://user-images.githubusercontent.com/73234020/158186390-0325f478-3a28-4c0a-a27e-d8ecd817a1a2.png)

* ### Server List After Deleting.

![ServerListAfterDeleting](https://user-images.githubusercontent.com/73234020/158186500-e03588be-2565-490b-92b0-9eb88d92977c.png)


## Thank you !!!


