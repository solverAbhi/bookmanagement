
# BOOK-MANAGEMENT ASSIGNMENT

Book Management System
This project is a Book Management System consisting of a backend server built with Node.js and Express.js and a frontend interface created using React.js. The backend server implements RESTful API endpoints for CRUD operations on books and uses MongoDB as the database to store book information. The frontend interface allows users to view a list of books, add new books via a form, edit existing book information, and delete books.

Backend
Technologies Used

Node.js
Express.js
MongoDB


## Setup Instructions for backend

To run tests, run the following command

```bash
  git clone https://github.com/yourusername/book-management-system.git

```
```bash
  cd book-management-system/backend

```
```bash
  npm install  and npm start
```
## frontend
The backend server will start running on http://localhost:3000.

API Endpoints

GET /api/books: Get a list of all books.

GET /api/books/:id: Get details of a specific book by ID.

POST /api/books: Add a new book.

PUT /api/books/:id: Update an existing book by ID.

DELETE /api/books/:id: Delete a book by ID.

Validation and Error Handling
Validation is implemented for book data (e.g., title, author, year) to ensure consistency and integrity.

Error handling middleware is in place to handle any errors and appropriate HTTP status codes are returned in API responses.
Frontend
Technologies Used

React.js


## Setup Instructions for frontend

To run tests, run the following command

```bash
  cd book-management-system/frontend

```
```bash
  npm install  and npm run dev
```
