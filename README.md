# My_Allocine_Ruby
Welcome to My Allocine, a project designed to explore and interact with a database related to the movie industry. This project focuses on leveraging SQL to manage and query data about movies, actors, directors, genres, reviews, and more. Whether you're a movie enthusiast or a data analyst, My Allocine provides a platform to delve into movie-related information with ease and efficiency.

# Task
In this project, the primary challenge is to effectively retrieve and manipulate data stored in a relational database using SQL queries. The complexity lies in managing relationships between tables (such as movies, actors, directors). Also in performing operations like filtering, aggregating, and joining data to answer specific questions about movies and their attributes.

# Description
To tackle the challenges presented, this project utilizes a series of SQL queries tailored to interact with multiple tables in the database. Queries include selecting all actors, retrieving movies by genre, aggregating review ratings, and more. The goal is to provide comprehensive insights into the movie database, allowing users to explore relationships between entities and extract meaningful information effortlessly.

# Installation
To get this project there are any options. You can fork it from my github repo. Or you can download as a zipfile from my github repo straight to your computer locally.
Make sue of this link to install the database{wget https://storage.googleapis.com/qwasar-public/track-claris/movies.db}.
after installing the database you can now test all the requests.

Usage
To use My Allocine effectively, follow these SQL query pattern: SELECT (With this query you list the coulum you want to work with , it can be multiple colummns ina a table) FROM (With the query you list the table you want data from ) JOIN movies_genres mg ON m.id = mg.mov_id JOIN genres g ON mg.gen_id = g.id WHERE (With this query you can provide a list of conditions or restrictions to follow );

