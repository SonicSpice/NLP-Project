# Introduction

**Webpack - NLP Project - Summary**
<br /> This project is configured using webpack to bundle resources for the client app. The server app integrates with the MeaningCloud API for NLP (Sentiment Analysis) queries by URL. The server endpoint takes user input (a valid URL) and delivers to the client app a breakdown of the sentiments found throughout an article or blog (as determined my MeaningCloud's NLP algorithm). This information is then displayed to the user in a chart which breaks down sentiments found in sentences throughout the article/blog.

# Clone or Fork Project

1.  Clone app using git (`https://github.com/SonicSpice/fend.git`) into a local directory.
2.  CD into the project folder using a terminal and run `npm install` to install project dependencies.
3.  Run `npm start` to concurrently run both the client app (using webpack dev server) and server app (using nodemon).

# How to Run Project

1. Dev build/serve script is `npm start`. This uses webpack-dev-server to build and launch the client index.html in browser.
2. Prod build/serve script is `npm run start:prod`. This uses webpack to build the prod dist/ files and then uses local live-server to launch dist/ in browser.

Note: Both dev/prod scripts will run the same backend-server process using nodemon.
Note: The backend-server express will read SERVER_PORT from a .env file.

# Primary Project Dependencies

- Bootstrap 4.5x
- FontAwesome
- Chart.js
- Webpack (for client-app)
- Nodemon (for server-app)
- Node/Express

# Author

Shawn Mak - Front End Web Development @ Udacity.

# License

**GNU GENERAL PUBLIC LICENSE**
