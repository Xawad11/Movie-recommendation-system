# Content-Based Movie Recommendation System


## Models Implemented
- **TF-IDF + Cosine Similarity** – baseline retrieval
- **KNN (TF-IDF space)** – efficient nearest-neighbor search
- **Hybrid (text + votes)** – combines textual similarity with numeric vote features
- **SVM Classifier** – multi-label genre prediction (supervised evaluation)
- **Clustering (LSA + K-Means)** – unsupervised grouping of movies

## Evaluation Metrics
- Retrieval: Precision@10, NDCG@10  
- Classification (SVM): Accuracy, Precision, Recall, F1, ROC/AUC  
- Clustering: Silhouette score, Genre purity

## Dataset
We used the **movies.csv** dataset (~4803 movies, ~24 features) containing metadata such as:
- Title, Overview, Genres, Keywords, Cast, Director  
- Numeric features: Vote average, Vote count, Runtime, Popularity, etc.  

## How to Run
- Open the notebook in Google Colab  
- Upload `movies.csv` to your Drive under `/ML Project/`  
- Run cells sequentially to preprocess, train, and evaluate models  
