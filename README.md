# A Brief Practical introduction to Firebase

## Zero-To-Hero: an Angular based Project
Downloading this project is not a requirement for the practical side of the talk, this is purely if you want to follow along.


## Requirements:

1. Node
   - To check this, you can run the following command:
     - `node -v`
     - This should return a version
     - e.g. `v12.14.0`
   - [I Need help installing Node](https://nodejs.org/en/)
2. Firebase CLI
   - To check this, you can run the following command:
     - `firebase --version`
     - This should return a version
     - e.g. `8.10.0`
   - [I Need help installing Firebase CLI](https://firebase.google.com/docs/cli#windows-npm)
     - I would recommend installing Firebase using NPM rather than the standalone binary, it's simply easier.
3. Angular CLI
   - To check this, you can run the following command:
     - `ng version`
     - This should return a version
     - e.g. `Angular CLI: 10.1.0`
   - [I Need help installing Angular CLI](https://cli.angular.io/)
4. A Google Account
   - This will be used to interact with Firebase

## Setup Steps:

1. Install the required packages using `npm`
   - You will need to run the following command:
     - `npm install` or `npm i`
2. Login to Firebase CLI using your Google Account
   - You will need to run the following command:
     - `firebase login`
