# Music recommender system

In this project, I dealt with two main types. 

- Content-based methods* gives recommendations based on the similarity of two song contents or attributes  
- collaborative methods* make a prediction on posible preferences using a matrix with ratings on different songs.


## Content-based methods

Advantages:
- Content-based methods provide personalized recommendations by focusing on the individual user’s preferences.
- These methods don’t rely on other users’ data, making them privacy-friendly.

Limitations:
- They only recommend items similar to what the user has already interacted with, leading to a lack of novelty.
- Requires extensive feature engineering and domain knowledge to extract meaningful attributes from items.


## Collaborative-based methods

Advantages:
- Serendipity: they can introduce users to items that they might not have discovered on their own, as recommendations are based on what similar users have liked.
- Easier to implement and doesn’t require extensive feature engineering.

Limitations:
- The performance can degrade when user-item interaction data is sparse
- Tends to favor popular items over niche ones, potentially reducing diversity in recommendations.

#

1) Generate a content-based music recommender system using a dataset of name, artist, and lyrics for +50000 songs in English.

2) Build a collaborative filtering music recommeder system using the Spotify Million Song Dataset.



## To Run

1. **Content-Based Recommender System:**
   - Ensure you have `songdata.csv` in the same directory.
   - Run `content_based_music_recommender.ipynb` to train and test the content-based recommender system.

2. **Collaborative Filtering Recommender System:**
   - For KNN-based system:
     - Open `knn_rec.ipynb` to train and test.
   - For Neural Network-based system:
     - Open `nn_rec.ipynb` to train and test.


## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- tensorflow/keras (for neural network-based methods)
- Additional libraries as specified in the individual notebooks and scripts

## Future Improvements

- Enhance the content-based recommender system by incorporating more sophisticated natural language processing (NLP) techniques.
- Improve the collaborative filtering system by experimenting with advanced models such as matrix factorization and deep learning approaches.
- Incorporate hybrid methods to leverage the strengths of both content-based and collaborative filtering systems.
- Expand to auditory and visual components, as current model is solely based on lyrics and play count