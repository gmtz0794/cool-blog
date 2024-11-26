# Cool Blog

This is a CMS-style blog site where developers can publish blog posts, comment on others' posts, and interact with the content. It is built using Express.js, Sequelize, MySQL, Handlebars.js, and express-session for authentication, all following the MVC architecture.

The application allows users to sign up, sign in, create and manage blog posts, and interact with comments. It is deployed on Heroku and follows best practices for web development.

## Installation

Clone the repository into your local machine: 

- git clone git@github.com:gmtz0794/cool-blog.git

Navigate to Main in project folder and install dependencies using:

- cd cool-blog
- cd Main
- npm install

Set up environment variables by creating a .env file in the root directory and add your MySQL database credentials:

- DB_NAME=<your_database_name>
- DB_USER=<your_mysql_username>
- DB_PASSWORD=<your_mysql_password>

Use the provided schema.sql file to create the necessary tables in your MySQL database and run the following command to seed the database:

- npm run seed

## Usage 

Start the application by using the following command:

- npm start

Visit http://localhost:3000 to view the homepage and interact with the blog features. When navigation the homepage, you will be presented with a navigation bar that includes: Home, Dashboard, Log in, Log out.

Users will not be able to create posts until creating a log in. When users click in Log in, a window will appear with the Username and Password sections to log in. If the user does not have a user, a sign up option will appear at the bottom the window.

Once the user creates an account, the opciont to create posts will be available in the dashboard section. This posts include the functionality of updating and deleting such posts.

When traveling back to home page, the posts will be shown with posted date.

## License

MIT License
