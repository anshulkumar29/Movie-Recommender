Movie-Recommender-System
This is a content-based movie recommender system built using the TMDb (The Movie Database) dataset. It recommends movies based on similarity in features such as genres, cast, crew, keywords, and more.

📂 Dataset
The project uses the following two files from the TMDb dataset: tmdb_5000_movies.xls tmdb_5000_credits.xls

🧠 Project Features
Preprocessing of data including parsing JSON columns
Feature engineering with genres, cast, crew, keywords
Text vectorization using CountVectorizer
Cosine similarity to measure movie closeness
Recommendation function based on similarity score
Deployment-ready using Streamlit
💻 Tech Stack
Python
Pandas, NumPy
Scikit-learn
NLTK
Streamlit for web interface
Pickle for model serialization 📦 Pickle Files The following files are used to store the processed data and similarity matrix: movies_dict.pkl similarity.pkl
