# Birthday Challenge

This project is to create a small web app that allows you to keep track of birthdays. When you open the app, you'll be able to see whose birthdays are today, or coming up in the next 2 weeks. It will also tell you how old they are (or will be).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites

You will need to have Node v7 and above installed on your system. To check if you have it installed type the following command in your terminal which will return your version.

```
node -v
```
You will also need to check that npm is installed along with node. To check type the following
```
npm -v
```
If you do not have node or npm installed, follow this [guide](https://nodejs.org/en/download/package-manager/).

## Installing

In order to install this project make sure you are in a directory you wish to install in your terminal and run the following command
```
git clone https://github.com/ochan7/birthday-challenge.git
```
then navigate into the folder and run
```
npm install
```
You will also need to navigate into the client folder and run the above command.

## Running the project

Open a terminal window from the root of the project and run 
```
npm run server
```
This will run the API at http://localhost:8081.

In a new terminal, navigate into the client folder and run
```
npm run start
```
This should open a new window with the front end of the application. If it does not you can open it at http://localhost:3000.

## Running the tests

There are two sets of tests, one for the back-end code and another for the front-end.
To run the tests for the back-end, run the following command from the root directory.
```
npm test
```

To run the test for the front-end, make sure the server and application are running and in a terminal from the client directory run the following command.
```
npm run cypress:run
```
If you wish the to see UI whilst also being tested you can alternatively run
```
npm run cypress
```

##
## Built With
* [react](https://reactjs.org/)
* [cypress](https://www.cypress.io/)
* [supertest](https://github.com/visionmedia/supertest)
* [mocha](https://mochajs.org/)
* [chai](http://chaijs.com/)
* [express](https://expressjs.com/)

## Authors

[Olie Chan](https://github.com/ochan7)