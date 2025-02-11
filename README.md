
echo "# 🚀 FastAPI Blog API" > README.md
echo "" >> README.md
echo "A **FastAPI-powered** Blog API with MongoDB for handling blog posts and comments." >> README.md
echo "Supports **CRUD operations**, MongoDB Query Operators (\`$match\`, \`$sort\`, \`$limit\`), and **JWT authentication**." >> README.md
echo "" >> README.md
echo "## **📌 Features**" >> README.md
echo "✅ **Create, Read, Update, Delete (CRUD) operations** for blog posts and comments" >> README.md
echo "✅ **MongoDB Query Operators** (\`$match\`, \`$sort\`, \`$limit\`)" >> README.md
echo "✅ **FastAPI with Pydantic Validation**" >> README.md
echo "✅ **Async Database Operations with Motor**" >> README.md
echo "✅ **Pagination & Sorting** for efficient queries" >> README.md
echo "✅ **JWT Authentication (Optional)**" >> README.md
echo "" >> README.md
echo "## **📌 1️⃣ Installation**" >> README.md
echo "" >> README.md
echo "### **🔹 Install Dependencies**" >> README.md
echo "First, install all required packages using **\`uv\`** (or \`pip\` if preferred):" >> README.md
echo "" >> README.md
echo "\`\`\`sh" >> README.md
echo "uv pip install -r requirements.txt" >> README.md
echo "\`\`\`" >> README.md
echo "or" >> README.md
echo "\`\`\`sh" >> README.md
echo "pip install -r requirements.txt" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "## **📌 2️⃣ Setup MongoDB**" >> README.md
echo "### **Option 1: Using MongoDB Atlas (Cloud)**" >> README.md
echo "1. **Go to** 👉 [MongoDB Atlas](https://www.mongodb.com/atlas)" >> README.md
echo "2. **Create a cluster**" >> README.md
echo "3. **Get your MongoDB URI** (Example):" >> README.md
echo "   \`\`\`" >> README.md
echo "   mongodb+srv://your_user:your_password@cluster0.mongodb.net/blog_db?retryWrites=true&w=majority" >> README.md
echo "   \`\`\`" >> README.md
echo "4. **Update \`db.py\` with your MongoDB URI**." >> README.md
echo "" >> README.md
echo "### **Option 2: Using Local MongoDB**" >> README.md
echo "1. Install **MongoDB Community Server** → [Download Here](https://www.mongodb.com/try/download/community)" >> README.md
echo "2. Start MongoDB:" >> README.md
echo "\`\`\`sh" >> README.md
echo "mongod --dbpath C:\data\db" >> README.md
echo "\`\`\`" >> README.md
echo "3. Use the local MongoDB URI in \`db.py\`:" >> README.md
echo "\`\`\`python" >> README.md
echo "MONGO_URI = \"mongodb://localhost:27017\"" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "## **📌 3️⃣ Running the FastAPI Server**" >> README.md
echo "Start the FastAPI server using **Uvicorn**:" >> README.md
echo "" >> README.md
echo "\`\`\`sh" >> README.md
echo "uvicorn main:app --reload" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "✅ **The API will now be available at:**" >> README.md
echo "👉 **Docs:** [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)" >> README.md
echo "👉 **ReDoc:** [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)" >> README.md
echo "" >> README.md
echo "## **📌 4️⃣ API Endpoints**" >> README.md
echo "### **🔹 Blog Posts**" >> README.md
echo "| Method | Endpoint           | Description                |" >> README.md
echo "|--------|-------------------|----------------------------|" >> README.md
echo "| \`POST\`  | \`/posts/\`          | Create a new blog post     |" >> README.md
echo "| \`GET\`   | \`/posts/\`          | Get all blog posts        |" >> README.md
echo "| \`GET\`   | \`/posts/{id}\`      | Get a post by ID         |" >> README.md
echo "| \`PUT\`   | \`/posts/{id}\`      | Update a post’s title/content |" >> README.md
echo "| \`DELETE\`| \`/posts/{id}\`      | Delete a post            |" >> README.md
echo "" >> README.md
echo "### **🔹 Comments**" >> README.md
echo "| Method | Endpoint               | Description                |" >> README.md
echo "|--------|-----------------------|----------------------------|" >> README.md
echo "| \`POST\`  | \`/comments/\`           | Add a comment to a post    |" >> README.md
echo "| \`GET\`   | \`/comments/{post_id}\`  | Get comments for a post    |" >> README.md
echo "| \`PUT\`   | \`/comments/{id}\`       | Update a comment’s text    |" >> README.md
echo "| \`DELETE\`| \`/comments/{id}\`       | Delete a comment          |" >> README.md
echo "" >> README.md
echo "## **📌 5️⃣ Running Tests**" >> README.md
echo "Run the Pytest tests to verify functionality:" >> README.md
echo "" >> README.md
echo "\`\`\`sh" >> README.md
echo "pytest tests -v" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "✅ **All tests should pass without errors**." >> README.md
echo "" >> README.md
echo "## **📌 6️⃣ Environment Variables (\`.env\`)**" >> README.md
echo "Create a \`.env\` file in the project root:" >> README.md
echo "\`\`\`" >> README.md
echo "MONGO_URI=mongodb://localhost:27017" >> README.md
echo "JWT_SECRET=your_secret_key" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "## **📌 7️⃣ Future Enhancements**" >> README.md
echo "- ✅ Add JWT Authentication" >> README.md
echo "- ✅ Integrate Docker for deployment" >> README.md
echo "- ✅ Implement User Roles & Permissions" >> README.md
echo "" >> README.md
echo "## **📌 8️⃣ Contributing**" >> README.md
echo "Pull requests are welcome! Fork the repo, make changes, and submit a PR." >> README.md
echo "" >> README.md
echo "## **📌 9️⃣ License**" >> README.md
echo "This project is **MIT Licensed**." >> README.md
echo "\`\`\`" >> README.md
echo "MIT License © 2025 AshishPython11" >> README.md
echo "\`\`\`" >> README.md
