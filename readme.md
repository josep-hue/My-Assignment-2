
# Assignment 2: Personal Portfolio Website

## INFR3120 Web and Scripting Programming

## Project Description

For this assignment, I created a personal portfolio website using Node.js, ExpressJS, and EJS. The goal was to build a website using Express routes and EJS templates instead of creating separate HTML files for each page.

My website includes four pages: Home, About Me, Projects, and Contact Me. I also used Bootstrap for the layout and Font Awesome for the icons.

## Technologies Used

* Node.js
* ExpressJS
* EJS
* HTML and CSS
* Bootstrap
* Font Awesome
* Git and GitHub
* Render

## Website Pages

### Home
Introduces my portfolio and includes a button to view my projects.

### About Me
Describes my interests in programming and web development, along with some of my technical skills.

### Projects
Displays information about my programming projects.

### Contact Me
Includes links to GitHub and LinkedIn.

## How My Website Works

I used Express routes in `routes/index.js` to connect each URL to its EJS page. I also used shared header, navigation, and footer files so that the layout stays consistent across all four pages.

## How to Run the Project

1. Install Node.js.
2. Open the project folder in Visual Studio Code.
3. Open the terminal and enter `npm install`.
4. Once the dependencies are installed, enter `npm start`.
5. Open `http://localhost:3000` in a browser

## Project Files

* `app.js` contains the Express application configuration.
* `routes/index.js` contains the routes for the four pages.
* `views` contains the EJS page templates.
* `views/partials` contains the shared header, footer, and navigation files.
* `public/stylesheets/style.css` contains the website's custom CSS.
* `package.json` contains the dependencies and startup command.

## GitHub and Deployment

I used GitHub to store my project and keep track of changes. I deployed my website using Render so that it can be accessed online without running it locally.

## References

I used the INFR3120 course lectures to understand ExpressJS, routing, EJS templates, and the overall project structure.

### ExpressJS and Express Generator
https://expressjs.com/

### EJS
Matthew Eernisse and contributors  
https://ejs.co/

### Bootstrap
Bootstrap contributors  
https://getbootstrap.com/

### Font Awesome
Fonticons, Inc.  
https://fontawesome.com/

### Node.js
OpenJS Foundation and contributors  
https://nodejs.org/


### CSS Flexbox

Source: MDN Web Docs by Mozilla
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout

I used CSS Flexbox to organize the page layout and keep
the footer at the bottom of the browser window.

