# Challenge 21: MERN Book Search Engine
![License badge](https://img.shields.io/badge/license-MIT_License-blue)

## Description

For this assignment, we were given starter code that has complete functionality using a RESTful API. We then had to refactor it to be a GraphQL API that uses an Apollo Server. For the back-end, we had to implement an Apollo Server and apply it to the Express middleware, make sure the auth middleware works with GraphQL, and create and define our queries and mutations in resolvers and typeDefs files. For the front-end, we had to create queries and mutations while also updating our App.jsx file to work with Apollo Provider and applying our queries and mutations to various files. Here were the User Story and Acceptance Criteria.

## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria

```md
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

## Deployed Application Link
[MERN Book Search Engine Deployed Application]()

## Screenshots of Application
Landing page
![Landing Page]()
Login/Signup
![Login or Signup]()
Book search results
![Book search results]()
Saved the book
![Saved the book]()
Profile/saved books page
![Profile and saved books page]()

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [License](#license)
- [Questions](#questions)

## Installation

Once this repo has been cloned to your local system and opened in VS Code, you will need to install all the required packages. In your terminal, run `npm i` and it will install the necessary packages.

## Usage

Run `npm run develop` in the terminal to run the application locally. It should automatically load the page.

## Contributing

N/A

## Tests

To run tests in the Apollo Server to make sure routes work, go to the localhost link with /graphql at the end.

## License
MIT License

---

## Questions

Any questions you may have, please feel free to reach out to me using either contact.<br>
GitHub Profile: https://github.com/ashpfander<br>
Email: ashmpfander@gmail.com