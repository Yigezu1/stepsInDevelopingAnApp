# stepsInDevelopingAnApp
## Here are the steps to create a web application using node

* We need to take discret steps in developing a web application using react as the front-end UI library. Therefore, application development can be divided into Back-End and Front-End Development.

### Part One - Back-End Development.
Here are the back-end development steps.
* Select the DMS (Database Management System for your application):- MySQL, MongoDB, ... etc.
* Create your schema based on the DMS you choosed for your application.
* Create the folder structure for the back-end of the application.
* Create the `server.js` file. This is the entry point for our application.
* Create the `model` for your application.
- We can have multiple models within our application. All the models can be put in a `models` folder.
* Create the `controllers` for our application.
- We could have multiple controllers in our application based on the requirement. All the controllers should be stored in the `controllers` folder in our application.


### Part Two - Front-End Development - Powered by React.
Here are the front-end development stes for applications whose UI is powered by React.
* Design the wireframes for your application.
* Based on the wireframes for your applications decide the number of pages you are going to create.
* Setup the boiler plate code either by copying from else where or by running `npx create-react-app <appname>` where `<appname>` be replaced by the name of your application. This will setup the initial folder tree for your front-end part of the application.
* Create the `components` for your application.
* Create the `pages` and related `states` for your application.
- The pages could have states of their own.
- State could be managed globally.

### Part Three - Testing.
* Perform end-to-end testing of your application.
### Part Four - Deployment.
* Create cloud database hosting account either for MySQL or MongoDb.
* Create application in Heroku and 
* Enable auto deployment feature of GitHub connect with an exiting application in Heroku.