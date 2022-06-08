
# Movie Recommendation System
![Python](https://img.shields.io/badge/Python-3.7-blueviolet)     ![Framework](https://img.shields.io/badge/Framework-Flask-red) ![Frontend](https://img.shields.io/badge/Frontend-React-green) ![API](https://img.shields.io/badge/API-TMDB-fcba03)

## Overview 
1. The web app is built using React.js for the frontend and python's flask for the backend.
2. It enable user to search and go through various details (like cast, genre, trailer, etc) for 5000+ movies (all these details are fetched using an API by TMDB) .
3. Based on the searched movie users are recommended movie which are fetched for the python-flask backend that uses local dataset and content-based filtering algorithm for recommendation.
4. The web-app also allows user to get top movies filtered by genre (these are also fetched using an TMDB api) . 

----

## Installation
1. Clone or download this repository to your local machine.
2.  Install all the libraries mentioned in the `requirements.txt` 
    ```shell
    $ pip install -r requirements.txt
    ```
 3. Then run the flask server by 
    ```shell
    $ python app.py
    ```
4. Go to the movie-recommender-app directory and install the node modules and build the project.
    ```shell
    $ cd movie-recommender-app
    $ npm install
    ```
5. Then build the project by
    ```shell
    $ npm run build
    ```
6. To the local flask server to start the project
    > `localhost : 5000`
    
7. If this doesn't work use 
    ```shell
    $ npm start
    ```
