# Movie Database

## Overview
This is a movie database application that displays a list of movies. Users can search for movies, filter them by genre, and sort them based on different criteria. The application is built using HTML, CSS, and JavaScript.

## File Structure

 ### index.html: The main HTML file containing the structure of the webpage.
 - A movie container (<div id="movie-container">) where the movie information will be displayed.
 - Two input elements: a search input and a genre filter dropdown.
   
### style.css: The stylesheet for styling the webpage.
 - The CSS file (style.css) provides simple styling for the movie boxes and layout of the webpage.

### script.js: The JavaScript file containing the logic for handling movie data, sorting, filtering, and updating the UI.
 - JavaScript Functions

1. createMovie(movieInfo)
* This function creates a movie box based on the provided movie information.
* It takes an array movieInfo as a parameter, containing details about a movie.
* It dynamically creates HTML elements to display the movie's title, year, director, duration, genres, and rating.
  
2. updateMovieContainer(moviesToAdd)
* This function updates the movie container with a new set of movies.
* It takes an array moviesToAdd as a parameter, representing the movies to be displayed.
* It clears the existing content of the movie container and appends new movie boxes based on the provided movies.
  
3. sortMovies(sortType)
* This function sorts the movies based on the specified criteria.
* It takes a string sortType as a parameter, indicating the sorting criteria ('yearUp', 'yearDown', 'bestRate').
* It sorts the movies array accordingly and updates the movie container.
  
4. searchAndFilter()
* This function is called when the user types in the search input or changes the genre filter.
* It retrieves the selected genre and search input values.
* Filters the movies based on the selected genre and search input simultaneously.
* Calls updateMovieContainer to display the filtered movies.
  
5. Event Listeners
* Event listeners are set up to call searchAndFilter when the user types in the search input or changes the genre filter.
  

## How to Use
* Open index.html in a web browser.
* Explore the list of movies.
* Use the search input to find specific movies.
* Use the genre filter to filter movies by genre.
* Sort movies by clicking on the "Year Up", "Year Down", or "Best Rating" buttons.
  
