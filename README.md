# Notes App Backend API

A simple RESTful API for managing notes, built using Node.js.
This project was developed as part of the Bangkit / Dicoding Backend learning path to demonstrate the implementation of a basic Notes API using JavaScript.

---

## 📌 Description

This project is a backend application that provides a REST API for managing notes data.

The API allows users to:

* Create notes
* Retrieve all notes
* Retrieve a specific note
* Update notes
* Delete notes

All data is stored in memory (array) without using a database.

---

## 🚀 Features

* RESTful API implementation
* CRUD operations for notes
* Unique ID generation
* Input validation
* Error handling
* JSON response format

---

## 🛠 Tech Stack

* Node.js
* JavaScript
* Nanoid (for generating unique IDs)
* REST API

---

## 📂 Project Structure

```
notes-app-back-end/
│
├── src/
│   ├── handler.js
│   ├── routes.js
│   ├── notes.js
│   └── server.js
│
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/ItqanFikri/notes-app-back-end.git
```

Go to the project directory:

```
cd notes-app-back-end
```

Install dependencies:

```
npm install
```

---

## ▶️ Run the Server

Start the server:

```
npm run start
```

or:

```
node src/server.js
```

Server will run on:

```
http://localhost:5000
```

---

## 📡 API Endpoints

### Create Note

```
POST /notes
```

Body example:

```
{
  "title": "My Note",
  "tags": ["personal"],
  "body": "This is my first note"
}
```

---

### Get All Notes

```
GET /notes
```

---

### Get Note By ID

```
GET /notes/{id}
```

---

### Update Note

```
PUT /notes/{id}
```

---

### Delete Note

```
DELETE /notes/{id}
```

---

## 🧪 Example Response

```
{
  "status": "success",
  "message": "Note created successfully"
}
```

---

## 🎯 Purpose

This project was created to:

* Learn backend development fundamentals
* Understand REST API implementation
* Practice CRUD operations
* Demonstrate backend development skills for portfolio

---

## 📚 Learning Source

This project was developed as part of:

Bangkit Academy / Dicoding
Backend Developer Learning Path

---
