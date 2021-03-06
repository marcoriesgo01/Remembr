# Project 2 - Remembr

## Website link:

Remembr is hosted on Heroku. Click on the link below to visit it.

[Remembr](https://remembr-memories.herokuapp.com/)

## Project:

Remembr is an application for seniors suffering from early stage dementia, caretakers, and medical professionals in Los Angeles. Through the application, members can find professionals they could potentially hire, see other users that are on a similar journey, discover and share new senior friendly places to visit, and see upcoming senior friendly events where they can feel part of a community as they age.


## Project Requirements:

This project's requirements are based on General Assembly's Project 2. See the project instructions at the link below:

[Project Requirements](https://git.generalassemb.ly/ira/SEIR-FLEX-123/tree/master/projects/project_2)

Project approvals spreadsheet:

[Project Approvals](https://docs.google.com/spreadsheets/d/1fS22w516hrhnCq4oJuuUdUQXpVWzxLps8brO4I0ulJc/edit?pli=1#gid=978133499)

## Remembr User Stories:

User stories are public on Trello. Click on the link below to view them. Logging into Trello is not required.

[Project 2 User Stories - Remembr](https://trello.com/b/nAjLMVbR/project-2-remembr)

## Technologies Used:

* HTML

* CSS - used to style the website.

* JavaScript - used for quote API call. 

* jQuery - used to add the API retrieved quote to the homepage. 

* Ajax - used to make API call to Forismatic.

* API: Forismatic Quotes API

* EJS - used for application views.

* Node.js - used for backend JavaScript on Remembr network application.

* Mongoose - used for data storage in the database of the application.

* Express - used for the server framework of the application.

* RESTful Routes: Index, New, Create, Show, Edit, Update, and Destroy (Total Route Count: 40)

* Bcrypt - used for authorization: login, signup, logout, and password encryption.

* Bootstrap - used for basic site styling, including centering, buttons, and forms.

## Approach Taken To Complete Remembr:

1. Ideate and wireframe the site.

2. Setup the file structure and files.

3. Get all 7 routes working - get to MVP.

4. Setup the different pages for each category, as well as setting up the different routes for all of them, including show, edit, and delete.

5. Create authorization: users can log in, sign up, and log out. Also create different pages and route to access the different ways to log in.

6. Style all of the different pages and add Bootstrap.

7. Add the Quotes API using Forismatic quotes and add it to the home page using jQuery.

8. Setup Heroku and deploy the application.

## Remembr Wireframe:

![alt text](https://github.com/marcoriesgo01/project-2/blob/master/public/images/wireframe.png?raw=true)

## Stretch Goals Completed:

* Use EJS Partials

* Include portfolio-quality styling

* Use a CSS framework like Skeleton or Bootstrap

* Incorporate a 3rd Party API: Forismatic

* Inside README.md file:
    * Include User Stories
    * Include wireframes designed for application

## Main Challenges When Creating Remembr:

* Having users only see their own data by using additional relationships between the models. 

* Creating and tracking a lot of different routes and EJS pages that would create a good user experience and flow.

* Figuring out errors and managing deployment with Heroku.

## Unsolved Problems For The Future - Future Challenges:

* Add additional relationships between the models.

* Make each user have their own portal where they can store personal data, save posts from the boards, and take notes. This data should be user specific and only the active user should see it.

* Create functionality for users to message each other through Remembr.

* Allow users to comment on board posts and create meetups for similar interests.

* Order items by categories, such as date for events.


## API Used To Generate Inspirational Quotes:

Forismativ API - This API was used to generate random inspirational quotes. The quotes are added and deleted to the home page upon user request using jQuery, Ajax, JavaScript, and HTML. The following link is the Forismatic API main website.

[Forismatic API](https://forismatic.com/en/api/)
