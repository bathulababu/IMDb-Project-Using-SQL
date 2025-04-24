# IMDb Movie Analysis using SQL

This project involves analyzing movie data from the IMDb using SQL queries. The analysis is performed on a SQLite database and explores various aspects of the movie dataset, including movie details and director information.

## Project Description

The project aims to extract meaningful insights from the movie database using SQL. It covers a range of queries to retrieve information about movies, directors, and their relationships. The analysis includes finding total movie counts, filtering directors, identifying popular and high-budget movies, and determining directors with the highest revenue.

## Data

The data is stored in a SQLite database file named `movies.sqlite`. It contains two tables:

-   `MOVIES`: Contains information about movies, such as title, budget, popularity, release date, revenue, and director ID.
-   `DIRECTORS`: Contains information about directors, including name, gender, and department.

## Methodology

1.  **Database Connection**:
    -   Connecting to the SQLite database using the `sqlite3` library.
    -   Verifying successful connection to the database.
2.  **Data Retrieval and Analysis**:
    -   Executing SQL queries to retrieve specific information from the database.
    -   Using pandas to read the SQL query results into DataFrames for better readability and manipulation.
    -   Queries include:
        -   Retrieving all data from the `MOVIES` and `DIRECTORS` tables.
        -   Counting the total number of movies.
        -   Filtering directors by name (e.g., 'James Cameron', 'Luc Besson', 'John Woo').
        -   Using `LIKE` clause to find directors with names starting with 'Steven'.
        -   Finding distinct gender values in the `DIRECTORS` table.
        -   Counting the number of female directors.
        -   Retrieving directors with specific IDs using `LIMIT` and `OFFSET`.
        -   Finding movies with the highest popularity and budget.
        -   Identifying the highest-rated movie released after '2000-01-01'.
        -   Finding movies directed by a specific director (e.g., 'Brenda Chapman').
        -   Finding the director with the highest total revenue.
        -   Calculating the average budget of movies.
        -   Finding movies released after a specific date (e.g., '2011-01-01').
        -   Finding movies with popularity greater than 99.
        -   Ordering directors by total revenue generated.

## Libraries Used

-   sqlite3
-   pandas

## Usage

To run this project:

1.  Ensure you have Python installed.
2.  Place the `movies.sqlite` file in the appropriate directory (as specified in the notebook, or adjust the path accordingly).
3.  Run the Jupyter Notebook (`imdb-project-using-sql.ipynb`) to execute the SQL queries and view the results.

## Files

-   `movies.sqlite`: The SQLite database containing the movie and director data.
-   `imdb-project-using-sql.ipynb`: Jupyter Notebook containing the SQL queries and analysis.

## Key Insights

The project provides various insights into the movie data, such as:

-   Total number of movies in the dataset.
-   Details of specific directors and their films.
-   Trends in movie popularity and budget.
-   Identification of top-performing directors and movies.

## Author

\[Naveen Babu Bathula]
