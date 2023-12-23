# Movie Recommender System

This Movie Recommender System is a Streamlit-based application designed to provide movie recommendations based on user input.

## Overview

This project aims to offer movie recommendations by utilizing cosine similarity between movies. The system retrieves data from 'themoviedb.org' via their API to fetch movie information and posters. Using precomputed similarity matrices, it recommends movies similar to the user's selection.

## Features

- **Movie Selection:** Users can select a movie from the provided list.
- **Recommendation Display:** Upon selecting a movie and clicking 'Show Recommendation,' the system displays the top 5 recommended movies alongside their posters.
- **Movie Posters:** Posters are fetched from 'themoviedb.org' API to provide visual representations of the recommended movies.

## Technologies Used

- Python
- Streamlit
- Pandas
- Requests
- Pickle

## Setup

1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Run the application: `streamlit run app.py`.

## Usage

- Launch the app using `streamlit run app.py`.
- Select a movie from the dropdown menu.
- Click 'Show Recommendation' to view recommended movies and their posters.

## Credits

This project was created by [Your Name] as a part of [Course/Workshop/etc.].

## License

This project is licensed under the [License Name] License - see the [LICENSE](LICENSE) file for details.
