## HEROKU
https://shrouded-shelf-19749.herokuapp.com/ | https://git.heroku.com/shrouded-shelf-19749.git

db name = bookDb
user = book
password = book

mongodb+srv://book:book@bookdb.nartt.mongodb.net/myFirstDatabase?retryWrites=true&w=majority

# Description
Refactor a fully functioning Google Books API search engine built with a RESTful API as a GraphQL API built with Apollo Server. The original app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It was already set up to allow users to save book searches to the back end.

This assignment includes:

Setting up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API,
Modify the existing authentication middleware so that it works in the context of a GraphQL API,
Creating an Apollo Provider so that requests can communicate with an Apollo Server, and
Deploying the application to Heroku with a MongoDB database using MongoDB Atlas.
# User Story
AS AN avid reader<br>
I WANT to search for new books to read<br>
SO THAT I can keep a list of books to purchase<br>

# Acceptance Criteria
GIVEN a book search engine <br>
WHEN I load the search engine<br>
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button<br>
WHEN I click on the Search for Books menu option<br>
THEN I am presented with an input field to search for books and a submit button<br>
WHEN I am not logged in and enter a search term in the input field and click the submit button<br>
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site<br>
WHEN I click on the Login/Signup menu option<br>
THEN a modal appears on the screen with a toggle between the option to log in or sign up<br>
WHEN the toggle is set to Signup<br>
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button<br>
WHEN the toggle is set to Login<br>
THEN I am presented with two inputs for an email address and a password and login button<br>
WHEN I enter a valid email address and create a password and click on the signup button<br>
THEN my user account is created and I am logged in to the site<br>
WHEN I enter my account’s email address and password and click on the login button<br>
THEN I the modal closes and I am logged in to the site<br>
WHEN I am logged in to the site<br>
THEN the menu options change to Search for Books, an option to see my saved books, and Logout<br>
WHEN I am logged in and enter a search term in the input field and click the submit button<br>
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book <br>on the Google Books site and a button to save a book to my account<br>
WHEN I click on the Save button on a book<br>
THEN that book’s information is saved to my account<br>
WHEN I click on the option to see my saved books<br>
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, <br>and a link to that book on the Google Books site and a button to remove a book from my account<br>
WHEN I click on the Remove button on a book<br>
THEN that book is deleted from my saved books list<br>
WHEN I click on the Logout button<br>
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to <br>search for books and a submit button  <br>