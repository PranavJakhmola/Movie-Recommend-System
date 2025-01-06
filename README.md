# Movie Recommending System




This repository contains a simple web-based movie recommending system using The Movie Database (TMDB) API. The application allows users to search for movies, filter by genre, and view movie details including ratings and trailers.
Table of Contents


#	Features

•	Installation

•	Usage

•	Files

•	API Key

•	License Features

•	Search Functionality: Users can search for movies by title.

•	Genre Filtering: Movies can be filtered by genre.

•	Pagination: Navigate through different pages of results.

•	Movie Details: View detailed information including an overview, ratings, and trailers.

•	Responsive Design: The layout adapts to different screen sizes.

# Installation

1.	Clone the repository:

git clone https://github.com/yourusername/movie-recommending-system.git

2.	Navigate to the project directory:

cd movie-recommending-system

3.	Open index.html in your preferred web browser.

# Usage

1.	Open index.html in a web browser.

2.	Use the search bar to find movies by title.

3.	Click on genre tags to filter movies by genre.

4.	Navigate through the pages using the "Previous Page" and "Next Page" buttons.

5.	Click on a movie to view detailed information and watch trailers.

# Files

•	index.html: The main HTML file containing the structure of the web page.

•	style.css: Contains the styles for the web page.

•	script.js: JavaScript file that handles the interaction with the TMDB API and dynamic content updates.

# API Key

This project uses the TMDB API. Ensure you replace the placeholder API_KEY in script.js with your own API key from TMDB. To obtain an API key:

1.	Sign up at TMDB.

2.	Navigate to your account settings and select "API".

3.	Request an API key and replace the placeholder in script.js:

const API_KEY = 'your_api_key_here';

# License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project.
________________________________________
# Notes

•	Ensure you have a stable internet connection to fetch data from the TMDB API.

•	The application is intended for educational purposes and may require further enhancements for production use.
