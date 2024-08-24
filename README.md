# RESTful API Project

This is a basic RESTful API project built using Node.js, Express, and EJS. The application simulates a simple blog where users can create, read, update, and delete posts.

## Features

- **Create**: Add new posts with a username and content.
- **Read**: View all posts or see a single post in detail.
- **Update**: Edit the content of an existing post.
- **Delete**: Remove a post from the list.

## Installation

1. Clone the repository:
    cd restful-api-project
    (go to restful-api-project directory)
bash
    git clone https://github.com/yourusername/restful-api-project.git


2. Install dependencies (excluding node_modules and package-lock.json):
    
bash
    npm install


## Usage

1. Start the server:
    
bash
    node index.js


2. Open your browser and navigate to http://localhost:8080/posts to view all posts.

## Project Structure

plaintext
restful-api-project/
│
├── public/
│   └── style.css        # CSS file for basic styling
│
├── views/
│   ├── edit.ejs         # Template for editing a post
│   ├── index.ejs        # Template for displaying all posts
│   ├── new.ejs          # Template for creating a new post
│   └── show.ejs         # Template for displaying a single post in detail
│
├── index.js             # Main server file
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation

## Credits
- **Author**: Besta Dinesh
- **Contact**: [LinkedIn](https://www.linkedin.com/in/besta-dinesh-736599263