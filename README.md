# Model Collapse in AI

This project explores the phenomenon of model collapse in AI, specifically how quickly AI models degrade when trained on data that they generate themselves. The primary focus is on sentiment analysis using Amazon reviews, where reviews are classified as either positive (4-5 stars) or negative (1-2 stars).

## Overview

The project investigates:

1. **Model Training**: Training a sentiment classification model on various dataset sizes.
2. **Total Collapse Scenario**: Simulating a scenario where the model generates its own training data, leading to performance degradation.
3. **Collapse Rates**: Analyzing how different rates of self-generated data affect model performance.
4. **Lower Collapse Rates**: Examining the effects of small proportions of AI-generated data on model accuracy.

## Technologies Used

- Python

## Dataset

The dataset used consists of Amazon reviews, focusing on sentiment classification based on star ratings.

## Results

The findings highlight the importance of curating high-quality, human-verified data for training AI models. The project demonstrates that even small amounts of AI-generated data can negatively impact model performance.

## Installation

To run the code, clone the repository and install the necessary dependencies:
