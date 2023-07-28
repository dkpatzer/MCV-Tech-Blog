# MVC-Tech-Blog


## Description

This is a tech blog using the MCV paradigm. It uses Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication. It is deployed on Heroku. It is responsive and works on mobile devices. It uses Tailwind CSS for styling. It uses Craco for bootstrapping the React application with a pre-configured development environment. 
## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation
I began by iinitializing the app ( npm init -y) and installing necessary dependencies.  I made dotenv file and began working on the server.jsfile and the config file. Next I created the models and the routes. I made  views, controllers,a helper's, utils and the public folder, and their respective files, along with a gitignore file. I soent most of my time attempting to connect the routes and handlebars. 


## Usage


User Story

AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

Acceptance Criteria

GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts




## [Check out my deployed website](https://dp-mvc-tech-blog-49f8aee46f52.herokuapp.com/)

## Credits
The MCV Tech Blog was developed by David Patzer as part of the NU coding bootcamp. 

I obtained information from many sources: 

https://www.freecodecamp.org/news/the-model-view-controller-pattern-mvc-architecture-and-frameworks-explained/
https://sequelize.org/
https://www.npmjs.com/package/sequelize
https://www.digitalocean.com/community/tutorials/how-to-use-sequelize-with-node-js-and-mysqlhttps://www.youtube.com/watch?v=YNyGD4rakmc
https://developer.mozilla.org/en-US/docs/Glossary/MVC
https://www.infoworld.com/article/3202764/the-complete-guide-to-nodejs-frameworks.html

- https://chat.openai.com/: For text verification and assistance.

- Finally, I got help from reviewing the answers to the challenge given in the NU coding bootcamp.



