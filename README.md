# Movie-genre-prediction
Movie genre classification is important as theme based categorization can assist a viewer to efficiently sort through an ever-increasing catalogue of titles and rapidly retrieve movies of interest. 
I evaluated several machine learning models like Linear SVM, Binary and Multinomial Naive Bayes and XGBoost+Word2Vec for prediction of movie genres based on plot synopsis. 
Since a movie can belong to multiple genres, this becomes a problem of multi-label classification. I addressed this by transforming the binary classifiers using OneVsRestClassifier.
I observed that binary based models achieve a higher precision whereas rank-based model attain a greater recall score.
