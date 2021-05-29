# Node_js_Express_js_Fundamentals

node --version
npm --version


to excute

node app.js
node app



to create enviroment (like pipenv install --dev)
to install dependencies for the project
>>> npm install


dependencies for this project
for local use nodemon, for developement np2
npm i nodemon -D (or --save-dev)


in package.json
 "scripts": {
    "start": "node app.js",
    "dev": "nodemon app.js"     
  },

to run whole app (i thinks)
>>> npm start 

to run whole app with reload (--reload)
>>> npm start dev

NOw modify this to 
in package.json
 "scripts": {
    "start" : "nodemon app.js"     
  },


to uninstall bootstrap
>>> npm uninstall bootstrap



To remove pkg manually
-- kill package-lock.json
-- delete line of pkg in package json
>>> npm install