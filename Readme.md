# 📝 Blog Data Modeler – MongoDB Schema Design

This project demonstrates the design of a MongoDB database schema for a blogging platform using Mongoose.

---

## 🚀 Features

* User schema
* Post schema
* Comment schema
* Relationships using ObjectId references

---

## 🛠️ Tech Stack

* Node.js
* MongoDB
* Mongoose

---

## 📁 Project Structure

```
models/
  User.js
  Post.js
  Comment.js
server.js
```

---

## 💡 Schema Design

### 👤 User

* name
* email
* password

### 📝 Post

* title
* content
* author (ref: User)

### 💬 Comment

* text
* post (ref: Post)
* user (ref: User)

---

## ▶️ How to Run

```bash
npm install
node server.js
```

---

## 🌐 GitHub Repository

👉 https://github.com/Varshithkumars03/blog-data-modeler



## 👩‍💻 Author

**Varshith Kumar S**

---
