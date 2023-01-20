# Stake & Duelbits Crash Predictor
Predicts the out come using AI/ML based on previous 100 games.

Requirements:
pip install -r requirements.txt

To run this:
python main.py

# Introduction

The goal of this project is to develop a model that can predict the outcome of a crash gambling game. Crash gambling is a popular game in which players can bet on the outcome of a continuously increasing multiplier, with the potential to cash out at any time before the multiplier crashes.

# Data Collection

To train and test our model, we will collect data from online crash gambling website Stake.com and DuelBits.com. This data will include information such as the starting multiplier, the cash out multiplier, and the time at which the player cashed out. We will also collect information on the player's bet amount and the player's profit or loss.

# Data Preprocessing

Before training our model, we will preprocess the collected data to ensure that it is in a format that can be easily used for training. This will include cleaning the data, filling in any missing values, and normalizing the data to ensure that all features are on the same scale.

# Model Training

We will use a variety of machine learning models to train our prediction model, including regression and decision tree models. We will also use a technique called k-fold cross validation to ensure that our model is able to accurately predict outcomes on unseen data.

# Model Evaluation

After training our model, we will evaluate its performance using a variety of metrics, including accuracy, precision, recall, and F1-score. We will also use techniques such as confusion matrix to evaluate the model's performance.
