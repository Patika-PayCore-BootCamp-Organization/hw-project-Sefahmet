# hw-project-Sefahmet
# **Train Ticket Reservation System**

This project is a graduation project for Patika.dev - PayCore Java Spring Bootcamp.

The classes in this project are shown in the diagram.

Note: Since it will be an entry-level project, there will be no payment class. All tickets can be considered free.


![Untitled Diagram drawio](https://user-images.githubusercontent.com/58665552/151546703-253c78c8-1537-46f2-8efd-e110d6905ad7.png)

If I describe the attributes of the classes:

***Passenger:***

*passenger\_firstname: Name of the person.*

*passenger\_lastname: Surname of the person.*

*passenger\_email: email of the person.
passenge\_bod: Birth Date of the person.*


***Ticket:***

*ticket\_sitnumber: The seat number of the ticket.*

*ticket\_date: When ticked was bought.*

*ticket\_status: The ticket taken or not.* 

***Service: (TR: “tren seferi”)***

*service\_date: It includes datetime of service with hour and minute information.*

*station\_list: This list includes all stations by ordinary. First and last element means station names. (First Station -Last Station- 02-02-2022 07:45 Service)*

*The other classes which are **Line**, **Station** and **Train** are creates the services. Stations come together sequentially to form the Line. The Line and Train merge in the Service.* 
