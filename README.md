# Incorporating Machine Learning to Predict the Authenticity of Job Postings 

-- Project Status: Completed - August 2022

### Installation

To use this project, first clone the repo on your device using the command below:
```
git init
git clone https://github.com/hunterblum/Job-Fraud-Detection.git
```

### Objective

The main purpose of this project was to predict fake job postings, mainly based on the text-based job description. The results of this project
could be used to weed out fraudulent job postings from any website, such as Indeed or LinkedIn. 

### Partners
* Hunter Blum
* Mendelina Lopez
* Stephen Kuc

### Methods Used
* Exploratory Data Analysis (Bar charts, word clouds, etc.)
* Sample Balancing
* Machine Learning
* Text Mining

### Technologies
* Python
* Jupyter Notebook
* Google Colab

### Description

The dataset used for this project was sourced from Kaggle at https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction. We began this
project by creating various charts for exploratory data analysis. Our main takeaway from the charts was that our target feature (real or fake job posting) was not balanced, which could lead to poor-performing models. So, we cleaned our text data (removing stopwords, vectorizing) and balanced the data using undersampling. Then we trained a myriad of machine learning models using five-fold cross-validation. Finally, we calculated the accuracy and F1-score for each model and plotted them to compare our results. In the end, an undersampled Support Vector Machine based only on the text data was the best performing model, achieving an accuracy of over 94% and an F1-Score over 93%. 
