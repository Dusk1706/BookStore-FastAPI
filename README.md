### Bookstore Project
This project is a web-based bookstore application developed using FastAPI and PostgreSQL as the database. The application provides functionality for managing readers, books, and the relationship between readers and books (readers_books).
## Features
Readers: Users can create and retrieve information about readers. Each reader has a unique identifier, name, and additional details.
Books: Users can create and retrieve information about books available in the bookstore. Each book has a unique identifier, title, author, genre, and other relevant details.
Readers_Books: This feature allows users to establish a relationship between readers and books. Users can create and retrieve information about books read by readers or books owned by readers.
## Technologies Used
FastAPI: FastAPI is a modern, fast (high-performance), web framework for building APIs with Python.
PostgreSQL: PostgreSQL is a powerful open-source relational database management system used for storing and managing the application's data.
## Setup Instructions
Clone the repository to your local machine.
Set up a PostgreSQL database and update the database configuration in the project.
Install the project dependencies using pip install -r requirements.txt.
Run the application using uvicorn main:app --reload.
Access the application in your web browser at http://localhost:8000.

