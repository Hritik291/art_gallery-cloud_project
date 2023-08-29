# art_gallery-cloud_project
cloud based project for create an art gallery website

Online Art Gallery
Introduction:-
Purpose:-
Scope:-
An online art gallery is a website that displays artworks. Usually, the online gallery is run as a business, with the purpose of displaying the artwork being to promote it to potential buyers.

Objective:- 
The main objective of the project on online art gallery is to manage the details of arts, order ,order update ,customer . it manages all the information about arts, art gallery, painting. The project is totally built at administrative end and thus only the administrator is guaranteed the access. The purpose of the project is to build an application program to reduce the manual work for managing the arts,order, art gallery, order update, it also tracks the all details about the order  update, customer . 
System requirement:-
H/w requirements:-
Processor:-
Ram- 128 gb
Hard disk:- 20gb
Monitor –
Other hard ware comonets
 
S/w requirements:-
Operating system:- windows , linux
Language :- html,css, javascript 
Database:- mysql server,cloud
Browser;-  chrome, mozila etc.
Web server- aws


Function:-
This web project is consists of two view- 1- admin panel and another is client panel 
Where admin is responsible for whole database. Admin can perform all the designs, creates and update operations. Admin will be able to – may add new item in the data base, may update and delete the item in the database.
Also client who will use the application , it will be able to visit the website. Client will be able to select different types of paintings i.e. according to their intrese. The client will be able to search different painting with name .
Feature:-
-	Should make the admin able to login into the admin panel after authentication.
-	Admin can view entire available gallery in database.
-	Admin also insertt new painting ,new profile new categories.
-	View all client list and details.
-	Makew new admin ,delete or update the existing user,
Admin provide the security for the website

There are two types of system users.
The first is user, user can login and upload his information and also check another profile.
The second user is the administrative who have the capability for maintain the record. Admin manage the whole database. Admin is the person who will control the application by entering new events, by updating or deleting new events.
General constraints:
It is a web based application. So it required internet which required both hardware and s/w. frontend-html,css,………
Backend-
Dualcore process with 1gb ram



Assumption:- 
There are some number of factors that are consider to be fulfill to make the project work .
-	The website who  will made it is latest tool  available in the market, so it is assumed the user will use the latest web browser for working .

SPECIFIC REQUIREMENTS:-
Interface Requirements
User interface- 
There are two types of user interface
(1) Client interface- The minimal requirements are that the user would be able to communicate to the system using GUI. GUI is bases on HTML, CSS, JavaScript and different frameworks and libraries. Different GUI based component are used for the following actions. 
(2) Administrator Interface- The minimal requirements required for the administrator interface that the admin will access the control panel through a GUI using some web browser. The GUI again bases on HTML, CSS and JavaScript and different libraries and frameworks. Hyperlinks and buttons will be provided to the admin to perform different tasks.
Functional Requirement:-
This section described the features and process performed by the web site. Firstly, the following features of the system and their interaction with administrator are described check paintings, Delete artist Update profiles, Update User, and Delete User. Then the following features related to User are described: Search Paintings, Registration, and feedback, they are followed by a detailed specification of the functionality of the art gallery. Data definition will also be discus in this document .Data flow diagram will be provided in these documents.
ADD Artist profile:-
- This functional feature deals with the administrator. The admin can add new painting in the database by using the interface of the Art Gallery.
- The admin will enter the Artist name, Artist address, time, date and other details about profile.
- when admin can enter the data it can communicate the mysql for data store.
- after enter a message will shown to user and database be update.
-also error message show .if error are occurred when data update in database.
Delete artist profile:-
- This functional feature also deals with the administrator. The admin can delete Artist in the database by using the interface of the art gallery.
- The admin will delete the item in the database with the help of ID of the artist.
- The server with communicate the Mysql to delete the item in the database.
- after admin delete successfully it can show a message .
- if any error it also so a message “error”.
Make a new user:-
- This functional feature too deals with the administrator. The admin can make new admin in      the database by using the interface of the art gallery. But these user can not access all details   it access only few detaill.
- The admin will enter the name, username, email id and password of the new admin as input.
- it also need database communicate for storing data.
- a message also show when it can update .
- error message also show if any error are occurred.
Update Existing User:-
-This functional feature also deals with the administrator. The admin can update an existing user in the database by using the interface of the Art Gallery.
-The admin would edit the user name, user address and other details about the user using different UI.
-The server with communicate the Mysqli to update the item in the database.
-A success message will be shown to the user and database will be updated.
-An error message will be shown upon some error while updating the admin in the database.


New User Registration:-
- This functional feature deals with the user who is using the application’s front-end .He would have to register him before any detail.
- The user will enter his complete name, address, his phone number, email address to register him.
- The server with communicate the Mysqli to and the user will be added to the database.
- Database will be updated with a new user and a success message will.
- An error message will be shown upon some error while searching a specific item the database.
User login:- 
-The user may login to artist detail by using the credentials assigned to him upon registration.
- The user will enter his email address and password to login.
- The application will communicate to the database to check if the user has registered already.
- User will be logged in if the entered credentials meets the one in the database and a success message will be shown otherwise he will be asked to enter correct data.
- An error message will be shown upon some error while logging into the database.

Use case diagram:-
The diagram represents the main processes in Art gallery. Then they will be broken down into more specific, use cases depending on the included processes of the main use case. Each of these use cases explains how the system handles the actions or
scenarios requested by the user.

 
The UML Use Case Diagram is a design used as one of the Methodology on art gallery ,management system development. It represents the main functions or processes of the system as well as the specific processes included. They were also labelled properly to guide programmers and users about the structure of art gallery Management System.
Non-functional requirements:-
-Performance:- this website should easily accessible on the system having minimum interent speed.
-Less time to response it .
 Availability:- In case of any system crash a backup will be available to make the sytem live.
Security:- users information will be secure and he will be able to access only their own personal information.
Also user be able to:- 
	View articles/blogs about art,accessories, and painting in general.
	View the FAQ page to find answer to their question.
	Send a message to the admin/seller via contact form.
	Navigate easily and intuitively throughout the site.


Logical database requirements:-
Er diagram:-







 
Class diagram:-

Sequence Diagram:-
The designed sequence diagram illustrates the series of events that occurs in art gallery Management System. In this illustration, the actors are represented by a stick man and the performance or classes are represented by objects. It will give you clear explanation about the behavior of an art gallery  in terms of processing the flow of instructions.
 
This designed sequence diagram is able to show programmers and readers about the sequence of messages between the actor and the objects.











 Data Flow Diagram (DFD)
Context Diagram:-
 
Level 0 diagram:-
 

Level 1 artist features diagram:-
 
Level 2 diagram of admin features:-
 
