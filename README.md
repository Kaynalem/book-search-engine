# Book Search Engine
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description
A Google Books API search engine application which allows users to search and save books to their profile.
This app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API. Modified existing code by replacing the existing RESTful API with an Apollo Server to use GraphQL queries and mutations to fetch and modify data as well as modified the existing authentication middleware so that it works in the context of a GraphQL API
![mockup](https://raw.githubusercontent.com/Kaynalem/book-search-engine/master/assets/mockup2.PNG)
![mockup](https://raw.githubusercontent.com/Kaynalem/book-search-engine/master/assets/mockup.PNG)
## Deployed Application
[Click here](https://kaynalem-book-search.herokuapp.com/) to use the deployed application!
## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)
## User Story

```
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria

```
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
```
## Installation
To install necessary dependencies, run the following command in your terminal:
```
npm install 
```
## Usage
Run `npm start` in your terminal and visit http://localhost:3001/ or [click here](https://kaynalem-book-search.herokuapp.com/) to use the deployed application!
## License
This project is licensed under the MIT license.
## Contributing
If you would like to contribute please file an issue
## Questions
If you have any questions about the repo, open an issue or contact me directly at [kaynalem@gmail.com](mailto:kaynalem@gmail.com).  
You can find more of my work at my [Github](https://github.com/kaynalem) page.
