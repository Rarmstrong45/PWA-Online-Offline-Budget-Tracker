# PWA-Online-Offline-Budget-Tracker

## Project Description

This project takes provided starter code for a database enabled budget tracker and converts it into a functional Progressive Web Application (PWA) with offline access and functionality. The browser Cache API is used to store the application's HTML, CSS, and JavaScript, controlled by a service worker. Offline transactions are stored using Indexed DB and are automatically uploaded when a connection is restored. A manifest file is also provided to allow the application to be downloaded to a browser, tablet, or phone.

## Tools Used
* JavaScript
* Node.js
* Express.js
* MongoDB and Mongoose
* Browser Tools
  * Cache API
  * Indexed DB
* npm packages
  * morgan - http request logger middleware used to track online and offline requests in development
  * compression - response compression middleware

## Installation

If you would like to view the code on your own device, clone the code into a project folder. From the project root directory, type npm install to install the necessary packages. Poke around and see how it works!

## Usage

The application is deployed on Heroku at https://obscure-taiga-93952.herokuapp.com/

## Screenshot

![Here is a screenshot of the PWA Budget Tracker.](PWA-Online-Offline-Budget-Tracker/public/images/Screenshot.JPG)
