# G6WebAppProject

KULLIYYAH OF INFORMATION AND COMMUNICATION TECHNOLOGY
DEPARTMENT OF INFORMATION SYSTEM
INFO 3305 WEB APPLICATION DEVELOPMENT 
SECTION 1
SEM 2 2020/2021
GROUP 6 PROJECT PROPOSAL 
PREPARED BY:
1
MOHAMAD NAZMI BIN NAZARUDIN
1811239
2
NUR ASIMAH BINTI CHE MAMAT
1813212
3
MOHAMMAD AIMAN BIN MOHAMAD ARES
1817363
4
WAN AHMAD LUQMAN AL - HAKIM WAN AZMI
1814213

TABLE OF CONTENT 
1.0 INTRODUCTION
2.0 OBJECTIVE
3.0 FEATURES AND FUNCTIONALITIES OF THE WEB APPLICATION
4.0 THE VIEWS, CONTROLLER, ROUTES AND MODELS. ERD FOR DATABASES TABLES. 
       4.1 ENTITY RELATIONSHIP DIAGRAM (ERD)
       4.2 SEQUENCE DIAGRAM- CUSTOMER LOGIN
       4.3 SEQUENCE DIAGRAM - CHOOSE FOOD
       4.4 SEQUENCE DIAGRAM - CONFIRM ORDER
       4.5 SEQUENCE DIAGRAM - DELIVER
5.0 REFERENCES

1.0 INTRODUCTION

This website is just a simple food delivering system which takes place in the university especially in International Islam University Malaysia(IIUM). Data is gathered from each user upon ordering the food from the specific cafeteria in different mahallah. The website application generally consists of a database and the whole part of the body is a PHP coding.

2.0 OBJECTIVE
To develop an application that will connect the IIUM community with the cafe to browse all the dishes, customize dishes to their requirements and place an order available at the mahallah cafe.
To ease the worker in taking orders from the customers.
To improve the communication between the client and the server and minimize the time of ordering.
Customers are able look for food that fits well in their budget as the prices of all items are mentioned in the menu.
To design an application that is able to accommodate huge amounts of orders at a time among the Mahallah residents and IIUM staff.

3.0 FEATURES AND FUNCTIONALITIES OF THE WEB APPLICATION

This system is an online food delivery method for a cafe where it will display all the menus available to the users.Firstly,the user are required to login to the system with their registered username and password before they were redirected to menu page.User can choose anything from the menu and all the selected menu will be displayed in checkout page.Once the user have confirmed the order,they will be updated with the runner that will delivered the food.the payment method required is by cash on delivery method.Since this system are only available for IIUM residents,it will allow the users to choose their preferred delivery spot from the choices of Mahallahs that are available under the delivery address.
All the criteria of the system are shown as follow:

Routes.
To create a request URL of the web project.Available in a folder with two common routes: web.php and api.php

Controllers. 
Classes that will be created to organize logic of the routes together in a place.It groups the similar routes together(on CRUD)..It will also be used to get the user inputs and process all the information accordingly.

Views. 
Our views will be presented by plain PHP templated.

Models (Database Tables with one-to-many relationship). 
Data will be represented by a model which is implemented by the Eloquent handling.

User Authentication
Works on the login page of the system where the user can have a secure implementation to the system.All the URL that is assigned to the system will be registered after installing the starter kits.

4.0 THE VIEWS, CONTROLLER, ROUTES AND MODELS. ERD FOR DATABASES TABLES. 

4.1 Entity Relationship Diagram
![alt text](https://github.com/aimanares/G6WebAppProject/blob/proposalImages/WebAppProject_ERD_4.jpg?raw=true)

4.2 Sequence diagram- customer login

4.3 Sequence Diagram - Choose Food
![alt text](https://github.com/aimanares/G6WebAppProject/blob/proposalImages/chooseFood.png?raw=true)

4.4 Sequence Diagram - Confirm Order
![alt text](https://github.com/aimanares/G6WebAppProject/blob/proposalImages/Confirm Order.png?raw=true)

4.5 Sequence Diagram - Deliver

5.0 REFERENCES

How to Model MVC Framework with UML Sequence Diagram? (n.d.). https://www.visual-paradigm.com/guide/uml-unified-modeling-language/how-to-model-mvc-with-uml-sequence-diagram/.

Objectives. Ordering System. (n.d.). https://ordering4103.weebly.com/objectives.html.

Ltd, O. I. S. P. (2019, November 11). Things to Consider While Opting for Food delivery app Development. Medium. https://smallbusinessforum.co/things-to-consider-while-opting-for-food-delivery-app-development-86de6d9774eb.




