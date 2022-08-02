# Task Manager - Test Automation Challenge

This application is a task manager and presents a UI for the user to manage the tasks.

## Description

This is an Angular application and allows the users to manage their tasks. The tasks are protected with user credentials. The application doesn't have any server or database connected, so the tasks will get reset on every restart of the application. There is one valid test user Username - user, Password - user which you can use to login with.

Angular CLI Version: 8.0.1 \
Angular Material Version: 8.0.0

## Requirements

Your challenge is to provide a test automation suite for this application. You are free to use either Cypress or WebdriverIO automation framework. The test automation should cover the following scenarios:
1. Login to the application
1. Validate landing page
1. Validate add and remove a task.
1. Validate marking/unmarking a task as done.
1. Validate all tasks page.
1. Validate favorites page.


## Pre-requisites

NodeJS needs to be installed on the system. Check if this is installed by running the command `node --version`. We recommed a version > 14

NPM needs to be installed on the system. Check if this is installed by running the command `npm --version`. We recommend a version > 7

Refer [NodeJS Downloads](https://nodejs.org/en/download/) to download NodeJS for your system.

## Running the application

```javascript

/* First, Install the needed packages */
npm install
// this code with the upstream dependency conflict issues, pls feel free to fix it or using --force, or --legacy-peer-deps
// as npm install --force / npm install --legacy-peer-deps

/* Then start the application */
npm start

```

This should automatically launch the browser at [http://localhost:4200/](http://localhost:4200/). Feel free to find and report any bugs in the application. Happy testing!

## Running end-to-end tests
Please put the notes on how to run the e2e tests
