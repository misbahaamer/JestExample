# Jest with Angular
This repository relates to the article ["Jest with Angular"](http://blog.skarby.info/jest-with-angular) - written on my blog ([blog.skarby.info](http://blog.skarby.info)).

It was also used as base for a presentation given at [ngAarhus](https://www.facebook.com/groups/ngAarhus) on October 30th, 2018.

# Angular CLI
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.2.

# Scripts
To start the application, or run scripts, there's no need to install any global dependencies. Make sure you're running a fairly
new version of `node` (eg. a LTS-release - this was developed using 8.x), and install the dependencies through `npm install`.

- To execute the application (in development mode), simply run the command: `npm start`
- To execute the tests (once), simply run the command: `npm test`
- To execute the tests (in watch mode), simply run the command: `npm run test:watch`

# QA:
# Problem 1: 
# Pick up any public website (google forms or any other site) which requires:
- Login
- Have data entry page
# Test case to develop:
# Create the automated UI testing using cypress https://www.cypress.io/
•	You should be able to login into the website
•	And verify that data is saved.

# Problem 2: 
# Set up the seed angular project using the below link:
https://angular.io/guide/quickstart
# Test case to develop
# Create “Snapshot test case” for page/component from above quickstart tutorial. 
You can refer the below tutorial :
https://jestjs.io/docs/en/snapshot-testing

