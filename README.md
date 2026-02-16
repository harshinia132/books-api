A simple REST API built using Node.js and Express.js to manage a list of books.

This project was developed as part of a Web Development Internship task to demonstrate understanding of REST principles, Express routing, and CRUD operations.

🚀 Features

Get all books

Add a new book

Update a book by ID

Delete a book by ID

In-memory data storage (no database required)

🛠 Technologies Used

Node.js

Express.js

JavaScript (ES6)

Postman (for API testing)

📦 Installation & Setup
1️⃣ Clone the Repository
git clone <your-repository-link>
cd books-rest-api
2️⃣ Install Dependencies
npm install
3️⃣ Start the Server
node server.js

Server will run on:

http://localhost:3000
📌 API Endpoints
🔹 1. Get All Books

GET /books

Returns all books.

🔹 2. Add a New Book

POST /books

Request Body (JSON):

{
  "title": "Atomic Habits",
  "author": "James Clear"
}
🔹 3. Update a Book

PUT /books/:id

Example:

PUT /books/1

Request Body (JSON):

{
  "title": "Updated Title",
  "author": "Updated Author"
}
🔹 4. Delete a Book

DELETE /books/:id

Example:

DELETE /books/1
