# Fake News Detection using Machine Learning

## Project Overview

The rapid growth of online news platforms and social media has made the spread of misinformation a significant problem. Fake news can influence public opinion, mislead readers, and create social or political confusion. Detecting fake news manually is difficult due to the large volume of information available online.

This project aims to develop a machine learning model that automatically classifies news articles as **Real** or **Fake** based on their textual content. The system uses Natural Language Processing (NLP) techniques to preprocess the text and convert it into numerical features, which are then used to train a classification model.

## Objectives

* Build a machine learning system to detect fake news articles.
* Preprocess and clean textual news data.
* Convert text data into numerical features using TF-IDF.
* Train a classification model to distinguish between real and fake news.
* Evaluate the model using standard performance metrics.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)

## Dataset

The dataset used in this project contains two CSV files:

* **Fake.csv** – Contains fake news articles
* **True.csv** – Contains real news articles

Each dataset contains the following columns:

* `title` – headline of the news article
* `text` – full article content
* `subject` – category of the news
* `date` – publication date

Dataset Source: Kaggle Fake and Real News Dataset.

## Machine Learning Workflow

1. Dataset collection
2. Data preprocessing and text cleaning
3. Feature extraction using TF-IDF
4. Train-test split of the dataset
5. Model training using Logistic Regression
6. Model evaluation
7. Prediction of new news articles

## Model Used

The primary model used in this project is:

Logistic Regression

Other models that can also be applied include:

* Naive Bayes
* Support Vector Machine (SVM)
* Random Forest

## How to Run the Project

### Step 1: Open Google Colab

Create a new notebook in Google Colab.

### Step 2: Upload the Dataset

Upload the dataset files:

* Fake.csv
* True.csv

### Step 3: Install Required Libraries

Install dependencies using:

pip install pandas numpy scikit-learn

### Step 4: Run the Notebook

Execute the notebook cells sequentially to:

* Load the dataset
* Preprocess the text
* Train the machine learning model
* Evaluate the model performance

### Step 5: Test Predictions

Provide a news sentence as input. The system will classify it as either **Real News** or **Fake News**.

## Results

The trained model typically achieves an accuracy between **95% and 98%** on the testing dataset, depending on preprocessing and training configuration.

## Future Improvements

* Use advanced deep learning models such as BERT for improved performance.
* Deploy the model as a web application using Flask.
* Integrate the model into a browser extension for real-time fake news detection.


