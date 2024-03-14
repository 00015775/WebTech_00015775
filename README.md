# WebTech_00015775

Student ID: 00015775

This WebTech CW2 is a basic CRUD-based online application that allows users to Add, Change, and Delete data from the applicant. It was completed by student ID 00015775. Users have the ability to add or update an individual's data, modify it, and save it. In the event that data is inaccurate or no longer valid, users can also remove it. A pleasant graphical user interface provided that shows the functions of each button visualy. In order to run the application there are several packages required to download on the terminal on Visual Studio Code which are : 

npm init -y ; this is for loading the node js packages.
npm i express express-validator pug body-parser nodemon ; enabling the feature of nodemon to work with node.
npm i epxress ; download the express for additional features to work.
npm i pug ; to view the visual interface pug packages required.
npm i install nodemon ; additional nodemon package to download.

After having installed those above given packages on the terminal on VS code, on the terminal we have to type "npm start" in order to start the web application, and by searching on the local browser "localhost:3000" online applicant can be viewed and used from there.

Link to GitHub public repo: https://github.com/00015775/WebTech_00015775

here below is shown the project structure of the web applicant:

/controllers
      /api/ticket/index.js
      /web/home/index.js

/data
    /mock_db.json

/public
      /css/style.css
      /js/scripts.js

/routes
      /api/ticket/index.js
          /index.js
      /web/home/index.js
          /index.js

/services
      /ticket/index.js

/validators
      /ticket/index.js

/views
    /home/add_update.pug & index.pug
    /layout.pug

