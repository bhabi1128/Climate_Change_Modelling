# Climate_Change_Modelling

## ABSTRACT

This project focuses on analyzing social media posts to understand user engagement and predict key engagement metrics such as likes and comments. Using a dataset containing post text, engagement counts, user identifiers, and timestamps, machine learning techniques are applied to extract meaningful insights. The project includes preprocessing of textual, categorical, and date-time features, followed by model training using regression algorithms to predict engagement levels. The results help understand what type of content drives higher engagement and demonstrate how machine learning can support social media analytics.
<br>
<br>

## PROJECT OVERVIEW

Social media platforms generate vast amounts of textual and interaction data. Studying this data helps understand how users react to different types of posts.
This project performs:

Data cleaning and preprocessing

Feature extraction from text and dates

Encoding of categorical user profiles

Engagement prediction (likes or comments)

Evaluation of machine learning algorithms

Interpretation of results

The dataset includes:

Post text

Date of post

Likes count

Comments count

User profile identifier

The goal is to build a pipeline that predicts engagement metrics and identifies patterns that influence social media interaction.
<br>
<br>

## PROJECT GOALS
1. Data Understanding and Cleaning

Handle missing values
Convert date into meaningful numerical features
Encode categorical columns
Extract text features using NLP
<br>

2. Feature Engineering

Generate year, month, day, hour features
Label-encode user identifiers
Use TF-IDF to convert text into numeric vectors
<br>

3. Model Development

Train machine learning models to predict engagement (likes or comments)
Compare algorithms to identify the best-performing model
<br>

4. Model Evaluation

Use metrics like RMSE, MAE, and R²
Validate model performance on unseen test data
<br>

5. Future Predictions

Apply the trained model to future or new data
Predict likely engagement for upcoming posts
<br>
<br>

# ALGORITHM USED

Random Forest Regression

Because:
It handles non-linear climate patterns.

Works well even with limited data.

Provides explainability through feature importance.

Robust and less prone to overfitting.
<br>
<br>

## FUTURE WORK
1. Advanced NLP Techniques

Use deep learning models like BERT or LSTMs

Detect sentiment, toxicity, or emotion in posts
<br>
2. Add Image/Video Features

Include multimedia features for better accuracy
<br>
3. Real-Time Prediction System

Build a dashboard for real-time engagement forecasting
<br>
4. User Behavior Profiling

Cluster similar users
<br>
Analyze how different user groups engage
<br>
5. Expand Dataset

Use larger and diverse datasets
<br>
Improve generalization of the model
<br>
<br>

## CONCLUSION

This project successfully demonstrates how machine learning can be used to analyze social media posts and predict engagement metrics. By converting raw text, categorical attributes, and timestamps into useful numerical features, the model predicts likes or comments with good accuracy. Random Forest performed the best among all tested algorithms. The study highlights how data-driven approaches can support content strategy, digital marketing, and social media performance optimization.
