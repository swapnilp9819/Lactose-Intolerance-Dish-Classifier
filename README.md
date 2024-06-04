# Lactose-Intolerance-Dish-Classifier

This project develops a machine learning model to classify dishes based on whether they are suitable for individuals with lactose intolerance. Utilizing text data (dish names) and employing a TF-IDF vectorized approach with a Linear Support Vector Classifier (LinearSVC), this project aims to assist those with dietary restrictions in making informed food choices.

## Introduction

The goal of this project is to accurately classify dishes as either containing lactose or being lactose-free based on their names alone. This solution can be particularly useful in applications like menu planning apps, dietary tracking, and nutritional advice platforms, where quick and accurate classification can significantly enhance user experience and dietary safety.


## Methodology

This project uses the TF-IDF vectorization to convert dish names into numerical data and trains a LinearSVC model. We chose LinearSVC due to its efficiency in handling high-dimensional data and its effectiveness in binary classification tasks.

## Results

The model achieved an accuracy of approximately 79% on the testing dataset, with a precision of 78% for the Lactose class and 79% for the Non-Lactose class, demonstrating the model's capability to classify dishes based on names with reasonable accuracy.

## Conclusions

The LinearSVC model performed well in classifying dishes for lactose intolerance, showing potential for further refinement and integration into dietary management tools.
