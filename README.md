# Movie-Recommendation-System

## Project Overview

This project presents a movie recommendation system designed to address common challenges like data sparsity, cold-start problems, and class imbalance. Using decision tree algorithms, the system aims to predict movie ratings based on user demographic and movie-related features from the MovieLens 1M dataset.

## Objective

The goal of this project is to explore the effectiveness of decision tree algorithms (Gini Index, Entropy, Gain Ratio) in building a movie recommendation system, and to compare their performance in terms of accuracy, efficiency, and interpretability.

## Dataset

- **MovieLens 1M** dataset from GroupLens
- Contains:
  - 1 million+ user ratings
  - ~3,900 movies
  - 6,000+ users with demographic details
- Data files used:
  - `ratings.dat`: UserID, MovieID, Rating, Timestamp
  - `users.dat`: UserID, Gender, Age, Occupation, Zip-code
  - `movies.dat`: MovieID, Title, Genres

## Preprocessing

- Cleaned movie titles and extracted release years
- Merged datasets on common keys (UserID, MovieID)
- Removed unnecessary columns (e.g., Timestamp, Zip-code)
- Encoded features: Age, Occupation, MovieID, Year
- Reduced dataset by sampling 40% for faster training
- Split data into 80% training and 20% testing sets

## Models and Algorithms

Three decision tree algorithms were implemented:
- **Gini Index**
- **Entropy**
- **Gain Ratio**

Each algorithm was evaluated based on:
- Accuracy
- Precision
- Recall
- F1-score
- Training time

## Results

- All three algorithms achieved similar accuracy (~38%)
- **Gini Index** had the best balance of precision and recall
- Class imbalance and limited features affected overall performance

## Future Work

- Explore hybrid models combining decision trees with collaborative filtering
- Incorporate additional features (e.g., user history, genre preferences)
- Investigate the use of "Movie Swarm" techniques for group-based recommendations

## Authors

- Lama Alotibie  
- Hessa Alshaya  
- Rimas Albahli  
- Atheer AlAsiri  
- Maymona Alotaibi  

King Saud University – College of Computer and Information Sciences


