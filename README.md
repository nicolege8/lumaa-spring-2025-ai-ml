# This repo includes my solution to the Movie Content-Based Recommendation prompt, using TF-IDF vectorization and cosine similarity.

1. **Dataset**
   - The dataset is a random sample of 500 entries from the Top Rated Movies according to TMDb dataset from Kaggle. The data includes relevant columns such as title, a short overview, and popularity
   - Here is the link to the dataset: https://www.kaggle.com/datasets/sumitsd4/top-rated-movie-dataset 

2. **Setup**
   - I used Python 3.12.3, and the dependencies can be installed through pip install -r requirements.txt. I created a virtual environment where I reinstalled numpy, pandas and scikit-learn.

3. **Running**
   - To run the code, you would open the jupyter notebook and run all the codeblocks. It will ask you to enter a short text description of your movie preferences, and will output five movies that match your preferences with similarity scores.

4. **Results**
   - After running the input "Romance with Comedy", I received the output of:

   Top recommendations:
   1. The Beach Bum (Score: 0.2421)
   2. Becoming Jane (Score: 0.2062)
   3. The Importance of Being Earnest (Score: 0.1946)
   4. Only Lovers Left Alive (Score: 0.1436)
   5. Vampire in Brooklyn (Score: 0.1262)
