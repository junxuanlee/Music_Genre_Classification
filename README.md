# Music_Genre_Classification

This project is a submission to a Music Genre Classification Hackathon at Machine Hack: https://machinehack.com/hackathons/music_genre_classification_weekend_hackathon_edition_2_the_last_hacker_standing/overview

Several data visualization techniques have been implemented:
1) Histograms
2) Pairplots
3) Boxplots
4) Violinplots

The following are the classifiers tested:
1) Decision Tree 
2) Random Forest 
3) Adaboost
4) Gradient Boost
5) Light Gradient Boost
6) Gaussian Naive Bayes
7) K-Nearest Neighbours (KNN)
8) Support Vector Machine (SVM)

The models were evaluated using cross-entropy loss. Confusion matrices were generated to investigate the models' performance.

To further improve the model performance, resampling is carried out to solve the issue of imbalanced class distribution. The following were the methods implemented:
1) Undersampling:
    i) Random Undersampling
    ii) Undersampling through clusters
2) Oversampling:
    i) Random Oversampling
    ii) Synthetic Minority Oversampling Technique (SMOTE)

PCA was carried out to learn which features/variables contributed the most to model perdictions.

It was finalized that the implementation with SMOTE and Gradient Boost Classifier achieved the best results.
