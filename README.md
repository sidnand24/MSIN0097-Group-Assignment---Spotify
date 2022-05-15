# The Effect of Spotify Playlists on Artist Success

This machine learning group project is part of the UCL MSIN0097 course Predictive Analytics. It focuses on using machine learning models to ascertain the determinants of artist success, defined as their ability to appear on specified target playlists. The models are then investigated to identify their ability to correctly classify those "successful" artists.

The study leverages **Warner Music Group's** rich database, in particular Spotify streams. The findings of the work can be used to optimise the allocation of resources when finding and promoting upcoming artists.

Following data exploration and visualisation, which includes network analysis, feature engineering was undertaken focused on three subtopics; artist, user and playlist features. Furthermore, principal component analysis (PCA) was employed to account for the region data of each stream. With a substantially imbalanced dataset, the use of SMOTENN provided a more equal distribution of target data.

The following models were adopted to classify successful artists:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- XGBoost
- Voting Classifier
- Artificial Neural Network

The XGBoost model was the best performing with a weighted average F1 score of **87%**. Music scouts can use such a model as a baseline to identify potential clients. Nevertheless, limitations on the imbalanced dataset and the omission of seasonal trends may influence results and detriment generalisability.
