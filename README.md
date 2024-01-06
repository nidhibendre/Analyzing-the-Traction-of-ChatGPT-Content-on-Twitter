# Analyzing the Traction of ChatGPT Content on Twitter

## Project Overview
This project focuses on analyzing traction metrics of ChatGPT content on Twitter. By examining various features of tweets, including text length, sentiment score, media presence, quoted tweet presence, mentioned users count, and hashtag count, we aim to classify the traction levels into "Little to no traction," "Moderate traction," and "High traction."

## Table of Contents
- [Project Description](#project-description)
- [Project Structure](#project-structure)
- [Data Analysis](#data-analysis)
- [Data Preparation](#data-preparation)
- [Models and Analysis](#models-and-analysis)
  - [Model 1: K-NN Classification](#model-1-k-nn-classification)
  - [Model 2: Random Forest Classification](#model-2-random-forest-classification)
  - [Model 3: Support Vector Machine](#model-3-support-vector-machine)
- [How to Use](#how-to-use)

## Project Description
The project uses Python and various libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn for data analysis, preparation, and modeling. We've categorized tweets based on their traction levels and built three different classifiers to predict these levels.

## Project Structure
- **Data Analysis:** Includes data inspection, cleaning, and visualization.
- **Data Preparation:** Involves feature engineering and data transformation.
- **Models and Analysis:** Detailed modeling processes for K-NN, Random Forest, and Support Vector Machine.
- **How to Use:** Instructions on running and replicating the project.

## Data Analysis
We imported the dataset from Kaggle, performed data inspection, handled missing values, and visualized tweet traction distribution.

## Data Preparation
We cleaned and preprocessed the data by removing non-English tweets, tweets with zero likes, and calculated sentiment scores. Additionally, we created new columns for media presence, quoted tweet presence, mentioned user count, text length, hashtag count, and traction categories.

## Models and Analysis
### Model 1: K-NN Classification
Explored K-Nearest Neighbors (K-NN) algorithm, tuned hyperparameters, and evaluated model performance.

### Model 2: Random Forest Classification
Utilized Random Forest Classifier, optimized parameters using GridSearchCV, and evaluated the model's accuracy and feature importance.

### Model 3: Support Vector Machine
Implemented Support Vector Machine (SVM) with hyperparameter tuning using GridSearchCV and assessed model performance.

## How to Use
1. Clone the repository.
2. Install the required libraries mentioned in `requirements.txt`.
3. Run the notebooks in sequential order: `Data_Analysis.ipynb`, `Data_Preparation.ipynb`, `KNN_Model.ipynb`, `Random_Forest_Model.ipynb`, and `SVM_Model.ipynb`.

