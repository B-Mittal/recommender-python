Collaborative Filtering Based Recommender for Books
This project implements a book recommendation system using collaborative filtering, a popular technique in recommender systems. Collaborative filtering predicts a user's interests by collecting preferences from many users (collaborating). The key files in this project are:

app.py: The main application script that handles the logic and routes for the web app, books.pkl: A pickle file containing book data, popular.pkl: A pickle file with data on popular books, pt.pkl: A pickle file storing the user-item interaction matrix, similarity_scores.pkl: A pickle file with precomputed similarity scores between items, index.html: The homepage of the web app, recommend.html: The recommendation results page.
How Collaborative Filtering Works:
Data Collection: Gather user preferences (ratings, interactions) for various books, Matrix Creation: Create a user-item interaction matrix from this data, Similarity Calculation: Compute similarity scores between items or users using methods like cosine similarity or Pearson correlation, Recommendation: Recommend items to a user based on the preferences of similar users (user-based) or similar items (item-based).
This approach leverages the collective preferences of the user base to provide personalized book recommendations.

I am uploading link to my books.pkl file as it can't be uploaded due to exceeding of the file size.
https://drive.google.com/file/d/1WEdVeFtCCxexgC1foSRCrjDGLyvUCBR6/view?usp=sharing

Screenshots of the project are as follows:
![image](https://github.com/B-Mittal/recommender-python/assets/168446223/a0215f35-82ab-422f-a124-67540efc9330)
![image](https://github.com/B-Mittal/recommender-python/assets/168446223/19c3781b-41a7-454a-a0c5-4e9fa9de8bcd)
![image](https://github.com/B-Mittal/recommender-python/assets/168446223/2673a94e-34ad-4517-a881-d2b3bf752a9c)



