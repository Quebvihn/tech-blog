# Tech Blog CMS

## Overview

The Tech Blog CMS is a content management system that allows developers to publish articles, blog posts, and share their thoughts and opinions within the tech community. Built from scratch and following the Model-View-Controller (MVC) architectural pattern, this web application provides a platform for developers to create, edit, and comment on blog posts.

## Features

- **Homepage**: The homepage displays existing blog posts (if any), navigation links to the homepage and the dashboard, and an option to log in.

- **Navigation Links**: Clicking on navigation links prompts users to either sign up or sign in.

- **User Authentication**: Users can sign up by creating a username and password. Once signed up, credentials are saved for future logins.

- **Dashboard**: The dashboard allows users to view existing blog posts, add new blog posts, and manage their posts.

- **View Blog Posts**: Clicking on the homepage or dashboard option in the navigation takes the user to the respective page, displaying existing blog posts with titles and creation dates.

- **View Individual Blog Post**: Clicking on an existing blog post shows the post title, contents, post creator’s username, creation date, and an option to leave a comment.

- **Commenting**: Signed-in users can leave comments on blog posts, which are saved and displayed with the comment creator’s username and creation date.

- **Update and Delete Posts**: Users can update or delete their existing posts from the dashboard.

- **Logout**: Clicking on the logout option in the navigation signs the user out of the site.

- **Session Timeout**: Users are prompted to log in again if idle on the site for more than a set time.

## Technologies Used

- **Handlebars.js**: Used as the templating language for rendering HTML pages.

- **Sequelize**: Serves as the Object-Relational Mapping (ORM) tool for interacting with the database.

- **Express-session npm package**: Manages user authentication and session handling.

## Deployment

The Tech Blog CMS is deployed on Heroku, providing a scalable and accessible platform for developers to share their insights and engage with the tech community.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up the database using Sequelize.
4. Configure environment variables for authentication and session handling.
5. Run the application using `npm start`.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the developers who contributed to this project and the open-source community for their valuable resources and support.