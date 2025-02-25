Udacity Final Travel App

This is the repository for the Final Project: Build a Travel App of the Udacity Front End Web Developer Nanodegree Program.

Project Overview:

The Travel App allows users to enter a destination and travel date to receive:

Location details (latitude and longitude)

A 16-day weather forecast

Images of the destination

Project Goals:

Implement asynchronous JavaScript to fetch data from external APIs

Use Webpack for building and bundling

Ensure responsiveness for various screen sizes

Implement offline support with Service Workers

Write unit tests using the Jest framework

Technologies Used:

Node.js (v20.11.1)

Express.js for the server

Webpack 5 for module bundling

Jest for unit testing

Axios for HTTP requests

SCSS for styling

Service Workers for offline functionality

APIs Used:

Geonames API: To get latitude and longitude from a location

Weatherbit API: To fetch 16-day weather forecasts

Pixabay API: To fetch images related to the destination

Custom Features:

Users can remove trips

Data is saved to Local Storage for persistence

Display multi-day weather forecasts with icons

Random image selection from Pixabay results

Prerequisites:

Ensure you have Node.js v20.11.1 or later installed:

node --version

Installation:

Clone the repository:

git clone https://github.com/YousefKhalil010/TravelApp.git
cd TravelApp

Install dependencies:

npm install

Usage:

Development Mode:

npm run dev

Production Mode:

Build the production bundle:

npm run build

Start the Express server on localhost:8081:

npm run start

Running Tests:

Execute all test cases using Jest:

npm run test

Node.js and Package Versions:

Node.js: v20.11.1

Webpack: v5.97.1

Webpack CLI: v6.0.1

Webpack Dev Server: v5.2.0

Jest: v29.7.0

Nodemon: v3.1.9

Additional Notes:

Ensure the .env file is properly set up with your API keys.

The app is not fully optimized for Safari input fields.

During the first server start, the Weatherbit API may occasionally delay responses.

Enjoy your travel planning!
"# TravelApp" 
