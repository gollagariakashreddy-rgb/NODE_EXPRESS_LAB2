# Lab 2: SQLite Database and CRUD Routes

**Name:** Akash reddy 
**Registration Number:** 252U1R6080  
**Section:** aiml 2-B

## Live Link
https://node-express-lab2-6u5i.onrender.com

## How to Run

**1. Install Dependencies**
```bash
npm install
```

**2. Start the Server**
```bash
npx nodemon app.js
```

**3. Test the API**

Open Postman and test the following endpoints.

## Endpoints / Scripts

| Method | Endpoint | Description |
|---|---|---|
| GET | `/books/` | Retrieve all books |
| GET | `/books/:bookId/` | Retrieve a book by ID |
| POST | `/books/` | Add a new book |
| PUT | `/books/:bookId/` | Update book details |
| DELETE | `/books/:bookId/` | Delete a book |

## Screenshots

Add your Postman screenshots here.

![Get All Books](screenshots/get-books.png)

![Get Book By ID](screenshots/get-book.png)

![Add Book](screenshots/post-book.png)

![Update Book](screenshots/put-book.png)

![Delete Book](screenshots/delete-book.png)

## Notes: Problems Faced and Solutions

- Faced difficulties connecting the Express server with the SQLite database.
- Solved the issue by properly initializing the database connection using async/await.
- Used parameterized queries to prevent SQL injection.
- Tested all CRUD operations using Postman.
