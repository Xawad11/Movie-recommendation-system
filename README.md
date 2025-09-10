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
We use a movie metadata file `movies.csv` (~4803 movies, ~24 features), which contains:
- **Textual features:** title, overview, genres, keywords, cast, director  
- **Numeric features:** vote_average, vote_count, runtime, popularity, budget, revenue  

The dataset can be downloaded here:  
[📥 Download movies.csv (Google Drive link)](https://drive.google.com/file/d/1cCkwiVv4mgfl20ntgY3n4yApcWqqZQe6/view)

To run the notebook:
1. Download the dataset from the above link.  
2. Upload it to your Google Drive under `/ML Project/movies.csv`  
   (or update the notebook path to match your folder).  
