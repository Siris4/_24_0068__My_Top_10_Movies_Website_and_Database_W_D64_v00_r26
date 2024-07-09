# My Top 10 Movies

This project is a web application built using Flask, SQLAlchemy, and Flask-Bootstrap. It allows users to maintain a collection of their top 10 favorite movies. Users can add new movies, update movie ratings and reviews, and delete movies from the collection.

## Project Structure

- `main.py`: The main Flask application file that handles routing, database models, and forms.
- `templates/`: Directory containing HTML templates for rendering the web pages.
  - `base.html`: Base template that other templates extend from.
  - `index.html`: Template for the home page displaying the top 10 movies.
  - `select.html`: Template for selecting a movie.
  - `edit.html`: Template for editing a movie's rating and review.
  - `add.html`: Template for adding a new movie.
- `static/css/styles.css`: Custom CSS file for styling the application.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/my-top-10-movies.git
cd my-top-10-movies
Create a virtual environment and activate it:
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Set up the database:
bash
Copy code
python main.py
Usage
Run the Flask application:
bash
Copy code
python main.py
Open your web browser and go to http://127.0.0.1:5000/ to access the application.
Features
Home Page: Displays the top 10 movies with their rankings, ratings, and reviews.
Add Movie: Allows users to add a new movie by entering the movie title. The application fetches movie details from the OMDB API.
Edit Movie: Allows users to update the rating and review of a movie.
Delete Movie: Allows users to delete a movie from the collection.
File Descriptions
main.py
Sets up the Flask application and configures the database.
Defines the Movie model for the SQLAlchemy ORM.
Handles routes for the home page, adding movies, editing movies, and deleting movies.
Uses Flask-WTF for form handling.
Templates
base.html: Base template with the basic HTML structure and Bootstrap CSS.
index.html: Home page template that displays the list of top 10 movies.
select.html: Template for selecting a movie (not currently used in main.py).
edit.html: Template for editing a movie's rating and review.
add.html: Template for adding a new movie.
static/css/styles.css
Custom styles for the web application.
Dependencies
Flask
Flask-Bootstrap
Flask-SQLAlchemy
Flask-WTF
WTForms
Requests
API
The application uses the OMDB API to fetch movie details. You need an OMDB API key to use this feature. Replace the placeholder key in main.py with your own API key.

Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.

vbnet
Copy code

This README provides an overview of the project, installation instructions, usage details, and information about the project's structure and dependencies. If you have any other requirements or modifications, please let me know!