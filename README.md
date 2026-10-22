
# BIC21203 Lab 4b – JSON and jQuery

**Name:** ANG KAI WEN  
**Student ID:** AI240154
**Lab b:** CLIENT-SIDE SCRIPTING (JSON and jQuery)

## Description

This lab focuses on creating JSON data, retrieving and displaying data using JavaScript fetch() and performing DOM manipulation using jQuery.

## How to Run

1. Open the project folder in Visual Studio Code.
2. Install the Live Server extension.
3. Right-click `books.html` and select "Open with Live Server".
4. Open `jquery-dom.html` using Live Server to test the jQuery operations.
5. An internet connection is required to load jQuery from the CDN.

## Files

- `books.json` – Contains information about two books.
- `books.html` – Retrieves and displays JSON data using fetch().
- `jquery-dom.html` – Performs DOM manipulation and button click events using jQuery.

## Question 1 – Create and Structure JSON Data

The `books.json` file contains two book objects in a top-level "books" array. Each book includes a title, author, publication year and genres. The JSON file was successfully parsed using PowerShell ConvertFrom-Json.

**JSON Data and Successful Parsing**

<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/d7b516ac-630a-4efc-a185-1e3097f0ce37" />


## Question 2 – Retrieve and Display JSON Data

The `books.html` file uses the JavaScript fetch() API to retrieve data from `books.json`. It displays the first book's title, the second book's author and the genres of both books. Error handling is included to display a message if the JSON file cannot be loaded.

**Successful Output**

<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/4aa35aec-6bc5-4731-82c2-8423ce632ccf" />
<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/57efd491-5018-4c3d-8921-01acb4ec17e3" />


**Error Handling**

<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/1cf56846-3fb8-4fe0-bc05-a56bea58ea3e" />
<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/41839976-5f7f-4f86-b650-2cb83c2777e6" />


## Question 3 – Compare Native JavaScript and jQuery

The `jquery-dom.html` file uses jQuery 4.0.0 to modify webpage elements. The `.text()` method changes the text, `.addClass()` applies a CSS class and `.on("click", ...)` handles the button click event.

**Page After Loading**

<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/8798593f-3dce-40d2-a8f4-328d96136311" />


**Button Click Event**

<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/e42b4a46-6433-45e8-9e9a-5960a4dce183" />

