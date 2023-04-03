# week3-Code-Challenge
This app displays a list of movies and allows the user to view more details about each movie and buy tickets for them.

## How to Use
To use the app, simply open the index.html file in a web browser. The app will display a list of movies with their titles and posters. Clicking on a movie will display more details about the movie, including its description, show time and run time. The user can also buy tickets for the movie by clicking the "Buy ticket" button. The app will update the number of available tickets and send a 'PATCH' request to the server to update the number of tickets sold.

## Code Overview
The 'displayAllMovies()' function fetches the list of movies from the server and displays them in the UI. The 'getSingleMovie()' function fetches the details of a single movie and displays them in the UI. The 'calculateAvailabeTickets()' function calculates the number of available tickets for a movie based on its capacity and the number of tickets sold.

The app uses 'fetch()' to communicate with the server and update the number of tickets sold when the user buys a ticket.

## How to Run the App
To run the app, simply clone the repository and open the index.html file in a web browser.

## Credits and Licensing
This app was created as part of a coding challenge. The server and movies data were provided by the challenge.
Author: Brian Rono
brianrono16@gmail.com
License: MIT License (see LICENSE file for details)