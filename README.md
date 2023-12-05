# StudentHousingFinder
Link to Business Requirement: https://docs.google.com/document/d/1HfzjBWUDes1UxDi9yob0D4R6YMiWGgLErjpFZMa3-3s/edit
Link to Functional Dependency: https://docs.google.com/document/d/1NBktMtUlr1iGigkE8cz2e_R3NzSCWksHU_thtI5k96I/edit
# Project Objective:
![Logo](screenshots/SH.png)
An application that lets users explore a list of student housing.

It will support:
* CRUD dorm/apartment listings
* Sort alphabetically and filter by location/building, cost, or by user input
* Owner/renter (user) sign-up/login 
* CRUD user information
* Users can rate dorm/apartment listings
* Monthly/annual statistics for owners/renters*
* Favorites for users*
* *We were not able to finish implementing these items.

_ Register and Sign In Note: _
> Because owners and students have different permissions for listings, page will look different depending on whether you sign up as an owner or a student.

@Domenic Lam implemented:
* Registering the owners and updating their listings as they post new housing listings.
* CRUD operations on the listings.
* CRUD operations on the messages between users and ensuring each message has one distinct sender and one distinct receiver.
* Making sure users are alloted separate accesses to listings than students are.

@Bernard Ekezie implemented:
* Registering the students and updating their ratings per listing.
* CRUD operations on the students and schools
* CRUD operations on the ratings
* CRUD operations on the user and ensuring users have a unique username and password.

## Authors:
Bernard Ekezie (https://github.com/bekezie) & Domenic (Ely) Lam (https://github.com/ely-lam)

UML Diagram
![Logo](screenshots/Project1_UML.png)

ER Diagram
![Logo](screenshots/Project1_ERD.png)
