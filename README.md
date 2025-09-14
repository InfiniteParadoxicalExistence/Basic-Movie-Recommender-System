# Basic-Movie-Recommender-System

A content-based movie recommender system built with Python and a dummy model was made, which can be deployed using Streamlit. The system leverages the TMDB dataset and applies text vectorization (Bag of Words) to recommend similar movies based on genres, keywords, and other features.

# Known Issues

- Network Dependency: The app fetches additional resources such as movie posters via the TMDB API.

- If there is no internet connection or the API rate limit is exceeded, posters may fail to load and connection errors can occur.

- Workaround: The core recommender system continues to work without posters. For full functionality, ensure you have a stable internet connection.

# Screenshots

  <img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/0f577b23-a1d0-4153-8601-75be5fd20a90" />

  <img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/2d8de727-1271-403e-b9df-71630ec4ac4f" />

