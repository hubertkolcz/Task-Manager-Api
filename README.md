# Task-Manager-Api
Project of API that allows to create users and assign tasks to them.

## Table of contents

* [Functionalities](#functionalities)
* [Technologies](#technologies)
* [Installation](#installation)
* [Available Scripts](#available-scripts)
* [Endpoints](#endpoints)
* [Screenshots](#screenshots)

_________________________________________________________________________________

## Functionalities

* Sign-up of user
* Loginning in
* Fetching user's profile
* Deleting user's account
* Uploading avatar for a user
* Updating user's data
* Sending emails

* Create task for user
* Fetching user's tasks
* Deleting user's tasks

_________________________________________________________________________________

## Technologies 
JWToken Authentication, Node.js, Mongoose (MongoDB), jest (for testing purposes), bcryptjs for encrypting and, validator for validating credentials and sendgrid for sending emails.

_________________________________________________________________________________

## Installation

* Once you clone the repostory, go to the directory where it is existing. Then, install dependencies with npm script command.
To install all the dependencies correctly, you need to use Node in version 12.*. You can switch to this version through NVM,
* After finishing the first step, make sure that your MongoDB database server is already running on port 27017.
* Now you should be ready. Start with npm run start or npm run dev, to test the program.

_________________________________________________________________________________

## Available Scripts & Installation

### `npm start`

Runs the app in the development mode on port 3000.<br />
To make requests, you need to use Postman.

You will also see any lint errors in the console.

### `npm dev`

Runs the app in the development mode.<br />

### `npm test`

Launches the test runner in the interactive watch mode.<br />

_________________________________________________________________________________

## Endpoints

Owierview of endpoints are available under the following link:
https://github.com/lyonzee/Task-Manager-Api/tree/master/endpoints

__________________________________________________________________________________

## Screenshots

<a href="https://ibb.co/zhTgLn5"><img src="https://i.ibb.co/SX4g1sx/API-postman-creating-user.png" alt="API-postman-creating-user" border="0"></a>
<a href="https://ibb.co/FmL6RqM"><img src="https://i.ibb.co/WG4nmpw/API-users-overview.png" alt="API-users-overview" border="0"></a>
<a href="https://ibb.co/6wkhK6J"><img src="https://i.ibb.co/B39Dh8K/API-tasks-overview.png" alt="API-tasks-overview" border="0"></a>
<a href="https://ibb.co/HGssmK5"><img src="https://i.ibb.co/SV88q6F/API-tests-passed.png" alt="API-tests-passed" border="0"></a>
