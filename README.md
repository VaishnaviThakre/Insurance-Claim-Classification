# Insurance Claim Classification

Welcome to the Insurance Claim Classification project! This repository contains a machine learning project aimed at classifying insurance claims. The goal is to predict whether an insurance claim is fraudulent or legitimate based on various features in the dataset.


## Table of Contents

- [Problem Statement](#ProblemStatement)
- [Objectives](#Objectives)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


##	Problem Statement

Health insurance is a crucial aspect of providing financial protection and improv-ing healthcare access for individuals and families. However, determining eligibil-ity for insurance coverage can be complex due to various criteria and factors, which can impact individuals' ability to secure insurance and access necessary medical care. Accurately predicting insurance claims is also important for insur-ance companies to manage risk, set premiums, and make informed decisions about coverage eligibility. To this end, logistic regression has been identified as a valuable statistical technique for predicting insurance claims.

##	Objectives

The objective is to investigate the utility of logistic regres-sion in predicting insurance claims and assessing eligibility for health insurance coverage. Developing a predictive model that helps insurers optimize their opera-tions, improve customer service, and mitigate financial losses by identifying high-risk policies or customers early on. The performance of models in predicting insurance claims based on available predictors will also be evaluated.

## Features

- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Machine Learning model training and evaluation
- Hyperparameter tuning
- Model deployment scripts

## Installation

To get started with this project, clone the repository and install the required dependencies.

```bash
git clone git@github.com:VaishnaviThakre/Insurance-Claim-Classification.git
cd Insurance-Claim-Classification
pip install -r requirements.txt
```

## Usage

1. **Data Preprocessing:** Prepare the dataset for training by running the preprocessing script.

2. **Model Training:** Train the machine learning model using the prepared dataset.

3. **Evaluation:** Evaluate the performance of the trained model on the test dataset.

4. **Prediction:** Make predictions on new data.


## Data

The dataset used in this project consists of various features related to insurance claims. The data is divided into training and test sets.

The dataset consists of nine columns, each providing unique insights into the characteristics and behaviors of policyholders. The age column provides demo-graphic information on individuals within the dataset, while the sex column of-fers insight into the distribution of genders among the insured population. The BMI column indicates the weight status of individuals, while the steps column offers insights into their activity level and lifestyle habits. The children column provides information on family size and responsibilities, while the smoker col-umn reflects lifestyle choices and potential health risks. The region column cap-tures geographical variations, while the charges column serves as the target vari-able for prediction. Finally, the insurance claim column indicates whether an insurance claim was made or not, serving as the outcome variable for predictive modeling.

## Model Training

The training script trains a machine learning model using the processed data. Various models and hyperparameters can be experimented with by modifying the configuration.

## Evaluation

The evaluation script computes performance metrics such as accuracy, precision, recall, and F1-score on the test dataset.

## Results

The results of the model evaluations, including metrics and visualizations. Detailed analysis and interpretation of these results can be found in the notebooks.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or create a pull request. Follow the guidelines below for contributing:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



Thank you for visiting the Insurance Claim Classification repository!Happy coding!

