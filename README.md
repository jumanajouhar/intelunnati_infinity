# Intel-Unnati Fake News Detection Using Python and Machine Learning

This repository contains a Python-based solution for detecting fake news articles using machine learning models. This project was done by Team Infinity of Saintgits College of Engineering, consisting of Jumana Jouhar, Neharin Tijo, and Meenakshi Mony, as part of the Intel Unnati Industrial Training Programme.

## Acknowledgements
We would like to thank our institutional mentor, Ms. Anju Pratap, for her support and guidance. We would also like to thank the industrial mentors for taking time out of their busy schedules to provide us with training and for answering our queries. We are very grateful to the Intel Unnati Team for this opportunity. We would like to extend our appreciation to anyone who has supported or helped us in one way or another.

## Introduction

Fake news has become a significant concern in today's digital age. This project utilizes machine learning techniques to distinguish between real and fake news articles. The solution is built using Python and leverages popular machine learning libraries such as scikit-learn and pandas.

## Objective

The objective of this project is to build a model that can accurately classify a piece of news as REAL or FAKE.

## Deliverables

- Data Collection: The ISOT Fake News Dataset was used. Exploratory Data Analysis was performed on the dataset.
- Data Preparation: The data was cleaned and prepared for training.
- Model Training: Various machine learning models were trained on the labeled news data.
- Model Evaluation: The performance of the models was assessed based on some important metrics.
- Parameter Tuning: Model parameters were tweaked to improve performance.
- Model Selection: The best-performing model was selected based on evaluation metrics.
- Making Predictions: The best model was used to classify new articles as real or fake.

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository to your local machine or download the source code as a ZIP file.
2. In the DevCloud terminal, use the following command to clone the repository:

```shell
git clone https://github.com/jumanajouhar/Intel-Unnati-Fake-News-Detection-Using-Python-and-Machine-Learning.git
```

3. Download the ISOT Fake News Dataset from the provided link (https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/) and extract the file.
4. Create a directory named "data" and save the extracted dataset in it.

```shell
mkdir data/
unzip News-_dataset.zip -d data/
```

5. Execute the `pip_env.sh` file to create the virtual environment named "fakenews" and a kernel named "fakenews" for your project.

```shell
bash pip_env.sh
```

6. Activate the "fakenews" kernel and run the `fakenews_detection.ipynb` Jupyter Notebook to start the project.

## Models

Several machine learning models can be used in a fake news detection project, but the models we chose are:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Passive Aggressive Classifier
- XG Boost

Parameter tuning and patching were done on the logistic regression model and it showed that Intel optimization did in fact help to improve our code runtime.

## Evaluation

The performance of the trained models was evaluated using various metrics such as accuracy, precision, recall, F1 score, AUC ROC score. Confusion matrices were also plotted to visualize the performance of the models.

Please refer to the project code and documentation for a detailed explanation.
