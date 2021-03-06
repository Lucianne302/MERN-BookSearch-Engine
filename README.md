# Book Search Engine Starter Code

## Table of Contents
* [License](#license)
* [Description](#description)
* [Installation](#installation)
* [Credits](#credits)
* [Contributors](#contributors)
* [Resources/links] (#resources/links)
* [Tests](#tests) 
* [Questions](#questions) 
* [Video] (#video)

## License
![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg) <br>

## Description
AS AN avid reader I WANT to search for new books to read SO THAT I can keep a list of books to purchase

GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  

## Installation
Start by running an "npm i" in your terminal followed by creating a .env file with the database name, username and password. npm run seed, followed by npm start. 

* npm i apollo-server-express
* npm install jsonwebtoken
* npx create-react-app client
* npm i apollo-boost graphql graphql-tag @apollo/react-hooks 
* npm install if-env
* npm install -D concurrently 
* npm install react-router-dom 


## Credits
Got help from TA

## Contributors
N/A

## Resources/links
Module 21: MERN
* NPM Express, https://www.npmjs.com/package/express-session <br> 
* NPM bcrypt, https://www.npmjs.com/package/bcrypt <br> 
* dotenv, https://www.npmjs.com/package/dotenv <br> 
* Apollo Mutations, https://www.apollographql.com/docs/tutorial/mutations/ <br> 
* Apollo Mutation Resolver, https://www.apollographql.com/docs/tutorial/mutation-resolvers/ <br>
* Apollo Schema, https://www.apollographql.com/docs/tutorial/schema/ <br>


## Test
We tested did end user testing and confirmed the global state was passing.  Unit tested for rendering component trees and running the complete application.   

## Questions
GitHub Username: Lucianne302 <br>
GitHub repo Link: https://github.com/Lucianne302/MERN-BookSearch-Engine.git <br>
Heroku link: https://hidden-lake-71005.herokuapp.com/ 
