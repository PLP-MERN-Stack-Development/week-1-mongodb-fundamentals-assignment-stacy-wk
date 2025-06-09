# MongoDB Fundamentals Assignment

This project demonstrates MongoDB fundamentals, including database setup, CRUD operations, advanced queries, aggregation pipelines, and indexing.

## Prerequisites

- **Node.js** (v18 or higher)
- **MongoDB** (local installation)
- **npm** (Node package manager)

## Setup Instructions

1. **Clone the repository**  
```
git clone https://github.com/PLP-MERN-Stack-Development/week-1-mongodb-fundamentals-assignment-stacy-wk.git cd week-1-mongodb-fundamentals-assignment-stacy-wk
```


2. **Install dependencies**  
```
npm install
```


3. **Start your MongoDB server**  
- For local MongoDB:  
  ```
  mongod
  ```

## How to Run the Scripts

### 1. Populate the Database

Run the following command to insert sample book data into your MongoDB database:
```
node insert_books.js
```


- This will connect to the `plp_bookstore` database and populate the `books` collection with sample data.

### 2. Run MongoDB Queries

- Open the MongoDB shell (`mongosh`) and switch to the `plp_bookstore` database:
```
use plp_bookstore
```
- Copy and paste queries from [`queries.js`](queries.js) into the shell to perform CRUD operations, advanced queries, aggregations, and indexing.

## Files

- [`insert_books.js`](insert_books.js): Script to insert sample book data.
- [`queries.js`](queries.js): Contains all required MongoDB queries for the assignment.
- [`wk1-mongodb`](wk1-mongodb): Contains screenshot of MongoDB Compass showing collection and sample data. 

