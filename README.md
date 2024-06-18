# Spam Detector - Module 13 Challenge Assignment

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation Instructions](#installation)
3. [Usage](#usage)
4. [Conclusions](#conclusions)
5. [Contribution Instructions](#contributing)
6. [License](#license)

## Project Overview

This **Spam Detector** project is designed to classify emails as spam or not spam using machine learning techniques. The project involves data preprocessing, feature extraction, model training & evaluation.

The provided background on the Module 13 Challenge Assignment:
 
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

## Installation Instructions

To run this project, ensure you have Python installed on your system and then install the required packages using the following command:

```bash
pip install -U scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone git@github.com:bychok/classification-challenge.git
cd spam-detector
```

2. Run the Jupyter notebook:

```bash
jupyter notebook spam_detector.ipynb
```

3. Follow the steps in the notebook to preprocess the data, train the model, & evaluate its performance.

## Conclusions

### Evaluate the Models

- Logistic Regression: 0.9262
- Random Forest Classifier: 0.9598

Based on the accuracy scores, the Random Forest Classifier model (0.9598) outperformed the Logistic Regression model (0.9262). So, this suggests that the Random Forest Classifier was better at predicting the labels in the testing data.

My prediction was that the Random Forest Classifier would perform better due to its ability to handle complex interactions between features & its robustness to overfitting. The results confirmed my prediction, indicating that the Random Forest Classifier was able to capture more subtle patterns in the data & also make more accurate predictions. Overall, these results highlight the importance of exploring different models & techniques to find the best approach for a given problem as well as the need to analyze the outcomes from multiple perspectives.

## Contributing Instructions

If you want to contribute, then please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
