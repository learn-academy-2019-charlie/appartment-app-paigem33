# Apartment App

This is a 3 day pairing activity.  It is intended to incorporate many of the skills you have learned up until now in the course, as well as prepare you for the group projects that are just around the corner.  Spend some time up front planning how you will build this application with your pair.

## User Stories

**Story:** As an un-registered guest on the website, I can go to a web page and see a list of available apartments.

Apartments have: two street designations, a city, postal code, state, and country, in a addition to a building manager's contact info, which includes: name, phone number, and hours to contact

**Story:** As an un-registered guest on the website, I can click on an apartment to view its details

**Story:** As an un-registered guest on the website, I can see a header element at the top of each page containing navigation to the other pages

**Story:** As a un-registered guest, I can go to registration page with a form and register as a new user. Once I have registered, I should be redirected to the index view of all apartments

**Story:** As a logged in user, I can go to a new apartment page with a form and create a new apartment

**Story:** As a logged in user, I can edit the information for any apartment I have created, but I cannot edit the information for apartments that belong to someone else

**Story:** As a logged in user, I should be able to log out

**Story:** As a registered user who has not logged in, I can go to a login page


## Discussion

* IMPORTANT NOTE
Remember that your rails app needs to be an API and should use a postgres database. You can include all of these requirements in your rails new command

* Hint: Only use one table in your database.
* Hint: Divide the story into smaller tasks and commit to git when each task is complete.


## Challenge 1 - Planning

* Draw out a proposed database schema
  - What tables do you anticipate you will need?
  - What associations
* Explore some of the free Bootstrap themes available, which one do you want to use?
* Draw out the main pages in the application?
  - What forms will you need?
  - What fields are on those forms?
  - Do your forms match your database schema?
* What are the user flows?
  - Protected vs. unprotected pages?
  - What is the most important user flow of the application?
    - Is this flow easy and intuitive for the user?


## Challenge 2 - Authentication

* Implement your authentication code, with stubbed out main pages


## Challenge 3 - Main UI
* Implement your main UI pages in your single page application
* Use data mocks to work with real data, but without the complexity of API integration


## Challenge 4 - API
* Finish off your application by hooking up the Database via API endpoints
* Is everything secure?
