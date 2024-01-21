 

# Node.js with MySQL Feedback Application

This is a simple feedback application built using Node.js and MySQL. The application allows users to perform CRUD operations on users, posts, and comments, and includes features such as viewing latest blog posts, retrieving positive comments, and deleting comments.

## Features

- **User Management:** Add users with user id, username, and email.
- **Post Management:** Add posts with post id, title, content, user id, created at, and ratings.
- **Comment Management:** Add comments with comment id, post id, user id, comment text, and ratings.
- **View Latest Posts:** View the latest three blog posts along with user details.
- **Retrieve Positive Comments:** Retrieve positive comments based on a post id and a ratings threshold.
- **Delete Comments:** Delete comments based on comment id.

## Technologies Used

- Node.js
- Express
- MySQL
- Body Parser
- Nodemon (for development)

## Getting Started

To run this application locally, follow these steps:

**1.Clone the repository to your local machine:**
 
   git clone https://santoshi-vajrangi.github.io/Project-on-Feedback-Application/


**2.Install dependencies:**

 
 
**3.npm install**
Set up your MySQL database. Update the MySQL connection details in server.js if needed.

Start the server:

 
 
**4.npm start**

pen your web browser and go to http://localhost:4500.

## Database Configuration

Ensure that you have MySQL installed, and configure the database connection in the `server.js` file:

```javascript
var con = mysql.createConnection({
  host: "127.0.0.1",
  user: "root",
  password: "",
  database: "feedback",
});

## API Endpoints

- **POST /users/insert:** Add a new user.
- **POST /posts/insert:** Add a new post.
- **POST /comments/insert:** Add a new comment.
- **GET /posts/view:** View the latest three blog posts.
- **POST /comments/retrieve:** Retrieve positive comments for a specific post.
- **POST /comments/delete:** Delete a comment by comment id.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## Author

Santoshi Vajrangi
**License**
This project is licensed under the ISC License - see the LICENSE file for details.

Author
Santoshi Vajrangi

 
