# Movie Review Application

## Overview
This is a full-stack application made with MongoDB for the database, Java and Spring Boot for the backend, and React for the frontend.The application features a separation of concerns between the client code and the server code. By implementing this loosely coupled architecture, these two parts (implemented using different technologies) can evolve in parallel and independently from one another.

## Features
* View a list of movies with their details in a carousel form.
* Watch trailers of movies.
* Post reviews for movies. 
* Responsive design to cater to different screen sizes.

## Tech Stack
* Frontend: React, Material UI, React Material UI, Bootstrap
* Backend: Java, Spring Boot
* Database: MongoDB

## Prerequisites
###  Ensure you have met the following requirements: 
* You have installed Node.js and npm.
* You have installed Java and Maven.
* You have installed MongoDB.

## Key Files and Directories
### Frontend
* Hero.js: Component that displays the movie carousel.
* Trailer.js: Component that displays the movie trailer.
* Hero.css: Styling for the Hero component.
* Trailer.css: Styling for the Trailer component.

### Backend
* MovieController.java: Handles HTTP requests.
* MovieService.java: Contains business logic.
* MovieRepository.java: Interface for MongoDB operations.

## Usage
1. Open your browser and navigate to http://localhost:3000.
2. Browse through the list of movies.
3. Click on the play button to watch the trailer.
4. Click on the review button to post a review.
   
