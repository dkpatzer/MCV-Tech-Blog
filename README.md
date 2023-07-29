# MVC-Tech-Blog


## Description

This is a tech blog built using the MCV paradigm. It allows users to post bogs about tech interests and readers to make comments and post their own blogs. It includes a login page and a dashboard for users to view their posts and make new posts. It is deployed to Heroku and uses JawsDB to allow mysql database functionality. 

This app was challenging for me to build and required much research and testing. I finally needed to create another directory and GitHub repository by renaming my inital project to get the app to work due to problems with database compatibility. I learned a lot by attempting to change the name of the app and directory, the database, the GitHub repsoitory and redploying the app to Heroku. I  learned a lot about the MCV paradigm, mysql2, sequelize and how to use them to build a full stack app. I also learned how to use JawsDB to allow mysql database functionality on Heroku.


## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation


I created my repository on Github and included a readme and gitignore for node js (actually I created two due to some issues with the first one). I cloned the repository to my local machine where I used VS Code and gitbash.

I initialized the app ( npm init -y) and installing necessary dependencies (including bcrypt, mysql2, sequelize and connect-session-sequelize, dotenv, epresss, express handlebars and express-session  and
"jest) and running npm install using the terminal while in the app directory. I was then able to use npm start to launch the application.

 I set up my mysql database and included a db folder with a schema.sql file. I created my database after logging into mysql, and selected it with the USE command. I then  seeded the database.
 
  After adding, commiting, and pushing my work to my GitHub repository, I created my Heroku app linking it with my git repository. I added JawsDB to my Heroku App to allow mysql database functionality. The app was fully deployed to the web page. 


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



![Screenshot React Portfolio Top of Site](![Screenshot MCV Tech Blog ]()




## [Check out my deployed website]()



## Credits
The MCV Tech Blog was developed by David Patzer as part of the NU coding bootcamp. 

I obtained information from many sources: 

-https://www.freecodecamp.org/news/the-model-view-controller-pattern-mvc-architecture-and-frameworks-explained/
-https://sequelize.org/
-https://www.npmjs.com/package/sequelize
-https://www.digitalocean.com/community/tutorials/how-to-use-sequelize-with-node-js-and-mysqlhttps://www.-youtube.com/watch?v=YNyGD4rakmc
-https://developer.mozilla.org/en-US/docs/Glossary/MVC
-https://www.infoworld.com/article/3202764/the-complete-guide-to-nodejs-frameworks.html
-https://dev.mysql.com/doc/refman/8.0/en/data-types.html
-https://www.sitepoint.com/node-js-mvc-application/
-https://coding-boot-camp.github.io/full-stack/heroku/deploy-with-heroku-and-mysql
- I reviewed the code from the following github repositories:
-https://github.com/JeffGoji/techblog/tree/main/public/javascript
-https://github.com/priyaravi23/mvc-tech-blog
-https://github.com/strossouw/MVC-Tech-Blog
-https://github.com/strossouw/MVC-Tech-Blog

- https://chat.openai.com/: For text verification and assistance.
-
- Finally, I got help from reviewing the answers to the challenge given in the NU coding bootcamp.



