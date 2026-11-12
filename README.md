# BIC 21203 – Lab 4b: Client-Side Scripting (JSON and jQuery)

## Project Description

This project was developed for Lab 4b of BIC 21203 Web Development. It demonstrates JSON data handling, retrieving JSON data using the JavaScript Fetch API, and DOM manipulation using jQuery.

## Learning Objectives

- Create and structure valid JSON data.
- Retrieve and display JSON data using the Fetch API.
- Compare native JavaScript DOM operations with jQuery.

## Project Structure

```text
Lab4b_JSON_jQuery/
│
├── books.json
├── books.html
├── jquery-dom.html
├── README.md
│
└── screenshots/
    ├── Q1/
    │   ├── q1-json (1).png
    │   └── q1-json-output (2).png
    │
    ├── Q2/
    │   ├── q2-books (1–5).png
    │   └── q2-books-output (6–7).png
    │
    └── Q3/
        ├── q3-jquery (1–4).png
        ├── q3-jquery-output (5–6).png
        └── q3-button-alert (7).png
```

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

## Screenshots

### Question 1 – JSON Data

![JSON Data](screenshots/Q1/q1-json-output%20(2).png)

### Question 2 – Fetch API

![Books Output](screenshots/Q2/q2-books-output%20(6).png)

### Question 3 – jQuery DOM Manipulation

![jQuery Output](screenshots/Q3/q3-jquery-output%20(5).png)

### Button Click Event

![Button Alert](screenshots/Q3/q3-button-alert%20(7).png)

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
