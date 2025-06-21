🌐 Social Media API
A backend RESTful API built with Node.js, Express, and Sequelize, designed as a full-stack learning project. It simulates core features of a social media platform, such as user registration, login, posting, commenting, and reacting.

📘 This project is a backend-only implementation intended for educational purposes and local testing. Authentication is handled using JWT tokens. The database is managed with Sequelize ORM and PostgreSQL.

🚀 Features
✅ User Authentication
Login / Logout with JWT access and refresh tokens

Token management via a refreshtoken model

Passwords hashed using bcrypt

📝 Posts
Create, read, update, and delete user posts

💬 Comments
Create, read, update, and delete user comments

❤️ Reactions
Create, read, update, and delete user reactions


📦 Technologies Used
Tech	Description
Node.js	JavaScript runtime
Express	Web framework for building the API
Sequelize	ORM for PostgreSQL
JWT	Authentication via tokens
bcrypt	Password hashing
dotenv	Environment variable configuration
morgan	HTTP request logger
PostgreSQL	Relational database backend

🔐 Environment Variables
Create a .env file in the root directory with the following variables:

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH__TOKEN_SECRET=your_refresh_token_secret
DATABASE_URL=your_database_connection_string

🛠️ Setup and Run
Install dependencies

npm install


Configure your .env file

Run the server

node app.js

Visit

The server runs by default on: http://localhost:3000

🧠 Learning Goals
Understand how to structure a full Express app with routing, models, and middleware

Learn how to handle user authentication securely

Explore Sequelize ORM for working with PostgreSQL

Build scalable APIs with real-world use cases like social platforms

📚 Future Improvements
Add user relationship (follow/unfollow)

Implement password reset feature

Uploading images 

Frontend (e.g. React) for user interaction
