
# TuneTrends

A Comprehensive Study on Regression, Classification, and Recommendations in Spotify Music

## Introduction
Music listening is one of the biggest universal experiences that technology has revolutionized. There has been a transition from personal music devices towards online streaming of music. This transition has been guided by music recommending systems based on genres and titles and events. Metadata has been widely used as an endorsement of the music. This shift has been most significantly noted in last fifteen years and has paved way for research in areas of music emotion recognition. This is based on valence which Spotify describes as “the musical positiveness conveyed by a track.”
## Problem Statement
The goal of this project is to implement:
1. Multi-linear regression to accurately predict the valence value.
2. Various classification algorithms to find which model achieves the highest accuracy in classifying valence-based classes.
3. Music recommender system based on the elements of the music provided in the dataset.
## Project Flow
1. **Data Preprocessing**
   - Handling Missing data
   - Handling Categorical data
   - Feature Scaling
2. **Exploratory Data Analysis**
3. **Multi-linear Regression** (valence prediction) 
   - Without any feature selection
   - Backward Elimination
   - BERT embeddings created for the categorical data
4. **Valence Classification** 
   - No Feature Transformation Techniques
   - with Principal Component Analysis (PCA) (unsupervised approach)
   - with Linear Discriminant Analysis (LDA) (supervised approach)
5. **Recommender System**
   - Recommendation through text vectors
   - Recommendation through music parameters
 
## Code Details
- Code 1 : **TuneTrend.ipynb** is a consolidated script that contains the project implementation.
- Code 2 : **BERT_file_for_spotify_project.ipynb** is the script to construct the BERT embeddings for all the categorical features.

## Acknowledgements

 - [Kaggle - 30000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs)


## Contributing
Contributions are welcome! If you have a bug fix, improvement, or a new feature to add, please follow these steps:
- Fork the repository
- Create a new branch
- Make your changes and commit them
- Push to the branch
- Open a Pull Request


## Contact
If you have any questions or suggestions, feel free to reach out to me:
- Email: hardik.sharma@temple.edu
- GitHub: hrdikshrma

Thank you for visiting TuneTrends ! Happy coding!
## Appendix

Learnings from this project:
1. Multi-Linear Regression 
2. Classification Algorithms
3. Feature Selection / Engineering
4. Feature Transformation (PCA & LDA)
5. K-Fold Cross Validation
6. Evaluation metrics calculation (R2 Score, MSE, RMSE, Accuracy, F1 Score)
7. BERT Embeddings Generation

