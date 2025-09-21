# Movie Recommender System

## Overview
This project is a **content-based movie recommender system** built with Python. It suggests movies similar to a given movie using metadata such as genres, keywords, and descriptions. The system demonstrates practical application of machine learning and data analysis in recommendation engines.

## Features
- Recommend movies similar to a selected movie.
- Uses a precomputed similarity matrix (`similarity.pkl`) for fast recommendations.
- Interactive: Users input a movie title to get suggestions.
- Easy to extend for hybrid or collaborative filtering.

## Technologies & Tools
- **Language:** Python 3.x  
- **Libraries:** pandas, scikit-learn, pickle, numpy  
- **Data:** CSV datasets and pickle files  

## Installation
1. Clone the repository:  
```bash
git clone https://github.com/kasamsaikiran87/movie-recommender-system.git
cd movie-recommender-system
Create a virtual environment (optional but recommended):

python -m venv venv
# Activate the environment
venv\Scripts\activate       # Windows
source venv/bin/activate    # Linux/Mac


Install dependencies:

pip install -r requirements.txt

Usage

Make sure movies.csv and similarity.pkl are in the project folder.

Run the main script:

python main.py


Enter a movie title to get recommendations.

Dataset

movies.csv contains movie metadata (title, genres, cast, keywords, ratings).

similarity.pkl stores the precomputed similarity matrix for faster computation.

Future Enhancements

Add collaborative filtering for personalized recommendations.

Build a web interface with Streamlit or Flask.

Include movie posters or trailers in the interface.

Author

Saikiran Kasam

GitHub: https://github.com/kasamsaikiran87

Email: kasamsaikiran87@gmail.com
