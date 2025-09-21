# Movie Recommender System

This is a **content-based movie recommender system** built using Python. It recommends movies similar to a selected movie based on genres, keywords, and metadata, demonstrating practical application of **machine learning**, **data analysis**, and **Python programming**.  

**Features:** Recommend movies similar to a given title, fast recommendations using a precomputed similarity matrix (`similarity.pkl`), user-friendly input for personalized suggestions, and modular code that is easy to extend.  

**Technologies & Tools:** Python 3.x, pandas, scikit-learn, pickle, numpy, and optionally Streamlit or Tkinter for UI.  

**Dataset:** Includes `movies.csv` with movie metadata (title, genres, cast, keywords, ratings) and `similarity.pkl` for precomputed similarity scores. Note: Due to GitHub file size limits, `similarity.pkl` may need to be downloaded separately if not included.  

**Installation:** Clone the repository with `git clone https://github.com/kasamsaikiran87/movie-recommender-system.git` and navigate into it. Optionally, create a virtual environment with `python -m venv venv`, activate it (`venv\Scripts\activate` on Windows or `source venv/bin/activate` on Linux/Mac), and install dependencies with `pip install -r requirements.txt`.  

**Usage:** Run `python main.py`, enter a movie name to get top recommendations, and optionally modify the recommendation count in the script.  

**Insights:** Discover movies similar to favorites, demonstrates **content-based filtering**, and can be extended to hybrid models for better personalization.  

**Future Enhancements:** Add collaborative filtering using user ratings, build a web interface with Streamlit or Flask, and include movie posters, trailers, or interactive visualizations.  

**Author:** Saikiran Kasam | GitHub: [https://github.com/kasamsaikiran87](https://github.com/kasamsaikiran87) | Email: kasamsaikiran87@gmail.com  

**License:** MIT License
