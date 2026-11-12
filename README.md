# BIC 21203 – Lab 4b: Client-Side Scripting (JSON and jQuery)

## Project Description

This project was developed for Lab 4b of BIC 21203 Web Development. It demonstrates JSON data handling, retrieving JSON data using the JavaScript Fetch API, and DOM manipulation using jQuery.

## Learning Objectives

- Create and structure valid JSON data.
- Retrieve and display JSON data using the Fetch API.
- Compare native JavaScript DOM operations with jQuery.

## Project Structure

Lab4b_JSON_jQuery/
│
├── books.json
│
├── books.html
│
├── jquery-dom.html
│
└── README.md

## Question 1 – JSON Data

The `books.json` file contains two book objects with the following properties:

- Title
- Author
- Publication year
- Genres

The JSON data was validated to ensure that it follows the correct JSON syntax.

## Question 2 – Retrieve and Display JSON Data

The `books.html` file uses the JavaScript Fetch API to retrieve information from `books.json`.

The webpage displays:
- The title of the first book.
- The author of the second book.
- The genres of both books, grouped by their titles.

Error handling is implemented using `try...catch`.

## Question 3 – jQuery DOM Manipulation

The `jquery-dom.html` file demonstrates three jQuery operations:

1. `.text()` – Changes the text to "Modified Text".
2. `.addClass()` – Adds the `myStyle` CSS class to the selected element.
3. `.on("click", ...)` – Displays an alert when the button is clicked.

The project uses jQuery 4.0.0 through the official CDN.

## How to Run the Project

1. Download or clone this repository.
2. Open the project folder using Visual Studio Code.
3. Install the Live Server extension.
4. Right-click `books.html` and select **Open with Live Server**.
5. To test jQuery, open `jquery-dom.html` using Live Server.

Note: An internet connection is required to load the jQuery CDN.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- JSON
- jQuery 4.0.0
- Visual Studio Code
- Google Chrome
- Live Server

## Course Information

**Course:** BIC 21203 – Web Development  
**Lab:** Lab 4b – Client-Side Scripting (JSON and jQuery)
