# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying whether a record is a candidate exoplanet from the dataset of observed objects.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)
 

## Assumptions and Findings

Before building the model, I expected SVM to predict the best results. The model's ability to classify data points based on a hyperplane makes it especially adept at classifying whether or not a planet would be an exoplanet. I expected Logistic Regression to also have a high model accuracy because it is especially good at answering binary questions like this one (it either is or isn't an exoplanet).

The model_comparison jupyter notebook file shows the results of each of the models, as well as graphs of importance features and model accuracies. As you can see, the Random Forest classifier has the highest accuracy, around 89%, whereas Logistic Regression, SVM, and Decision Tree all have 82-83% accuracies. This was different than I initially guessed. It makes sense that Random Forest would have a higher accuracy than Decision Tree because it is able to outline more complex relationships between data points.