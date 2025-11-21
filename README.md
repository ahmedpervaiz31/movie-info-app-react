A modern single-page application (SPA) for browsing popular movies and managing a personalized favorites list using the TMDB API.

Features

Popular Movies: Displays a grid of movies fetched from the TMDB API.

Search: Allows searching for movies by title.

Favorites System: Uses React Context and local storage for persisting favorited movies.

API Security: Integrates Vite environment variables (.env) for secure API key handling.

Tech Stack

Frontend: React (Hooks)

Build Tool: Vite

Routing: react-router-dom

State: React Context API

Data: The Movie Database (TMDB) API

Setup and Installation

Follow these steps to run the application locally:

1. Prerequisites

Node.js and npm (or yarn/pnpm) are required.

2. Clone the Repository

git clone [https://github.com/ahmedpervaiz31/movie-info-app-react.git](https://github.com/ahmedpervaiz31/movie-info-app-react.git)
cd movie-info-app-react/frontend


3. Install Dependencies

npm install


4. Configure API Key (Security)

This project uses environment variables to secure your TMDB API key.

Create a file named .env in the root of the frontend directory.

Get your API key from TMDB.

Add the key to the .env file using the required VITE_ prefix:

# .env
VITE_TMDB_API_KEY="YOUR_ACTUAL_SECRET_API_KEY_HERE"


5. Run the Application

Start the development server:

npm run dev
