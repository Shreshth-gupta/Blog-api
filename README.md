Blog API

Description
This project is a RESTful Blog API built using Node.js and Express.js. It allows users to perform CRUD operations on blog posts, including creating, reading, updating, and deleting posts.

Features
Get All Posts: Fetch all blog posts in the system.
Get Post by ID: Retrieve specific posts using their unique ID.
Create Post: Add new posts with title, content, author, and date.
Update Post: Partially update a post with new information.
Delete Post: Remove a post by providing its ID.
Technologies Used
Node.js: Server-side JavaScript runtime.
Express.js: Web framework for Node.js.
Axios: HTTP client for making API requests.
EJS: Embedded JavaScript templates for rendering views.
Prerequisites
Node.js installed
Git installed
Getting Started
Clone the Repository


git clone https://github.com/Shreshth-gupta/Blog-api.git
cd Blog-api
Install Dependencies


npm install
Start the API Server
Open a terminal and run:


node index.js
This starts the API server on http://localhost:4000.

Start the Frontend Server
Open another terminal and run:

node server.js
This starts the frontend server on http://localhost:3000.

Access the Web App
Navigate to http://localhost:3000 in your browser.

API Endpoints
GET /posts: Get all posts
GET /posts/
: Get a post by ID
POST /posts: Create a new post
PATCH /posts/
: Update a post
DELETE /posts/
: Delete a post


Folder Structure
Blog-api/
│
├── public/           # Static assets (CSS, JS)
├── views/            # EJS templates (index.ejs, modify.ejs)
├── index.js          # API server
├── server.js         # Frontend server
├── package.json      # Project metadata and dependencies
└── .gitignore        # Files to be ignored by Git


Example Usage
Create a Post
Send a POST request to /posts with the following JSON:
{
  "title": "New Blog Post",
  "content": "This is the content of the new post.",
  "author": "John Doe"
}
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
