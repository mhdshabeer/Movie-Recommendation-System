# Movie Recommendation System

## Overview
This project is a content-based movie recommendation system that suggests similar movies based on a given input movie title. It uses TF-IDF vectorization and cosine similarity to determine the closeness between movies based on their genres, keywords, taglines, cast, and director.

## Features
- Takes a movie title as input from the user.
- Finds the closest matching movie title from the dataset.
- Computes similarity scores based on textual features.
- Returns a list of the top 15 recommended movies.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity

## Dataset
The system uses a dataset containing movie information, which includes the following features:
- `title`: Name of the movie
- `genres`: Genres associated with the movie
- `keywords`: Important keywords describing the movie
- `tagline`: Movie tagline
- `cast`: Main actors in the movie
- `director`: Director of the movie

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install dependencies:
   ```sh
   pip install numpy pandas scikit-learn
   ```
3. Ensure you have the dataset (`movies.csv`) in the working directory.

## Usage
1. Run the script:
   ```sh
   python movie_recommendation_system.py
   ```
2. Enter a movie name when prompted.
3. View the recommended movies in the console output.

## Example
```
Enter Movie Name: Inception
Recommended Movies Are:
1 -> Interstellar
2 -> The Prestige
3 -> The Dark Knight
...
```

## Future Improvements
- Implement a graphical user interface (GUI) for better user interaction.
- Expand the dataset for more recommendations.
- Optimize performance for large datasets.
- Integrate with an API for live movie data.



