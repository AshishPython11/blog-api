# FastAPI Blog API

A **FastAPI-powered** Blog API with MongoDB for handling blog posts and comments.  

---

## ** Features**
- ✅ **Create, Read, Update, Delete (CRUD) operations** for blog posts and comments  
- ✅ **MongoDB Query Operators** (`$match`, `$sort`, `$limit`)  
- ✅ **FastAPI with Pydantic Validation**  
- ✅ **Async Database Operations with Motor**  

---

## **📌 1️⃣ Installation**

### **🔹 Install Dependencies**
First, install all required packages using **`uv`** (or `pip` if preferred):



## API Endpoints
🔹 Blog Posts
Method	Endpoint	Description
POST	/posts/	Create a new blog post
GET	/posts/	Get all blog posts
GET	/posts/{id}	Get a post by ID
PUT	/posts/{id}	Update a post’s title/content
DELETE	/posts/{id}	Delete a post
🔹 Comments
Method	Endpoint	Description
POST	/comments/	Add a comment to a post
GET	/comments/{post_id}	Get comments for a post
PUT	/comments/{id}	Update a comment’s text
DELETE	/comments/{id}	Delete a comment

