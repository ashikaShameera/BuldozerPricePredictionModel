# Bulldozer Price Prediction Model


This project uses machine learning model can use to predict the future sale prices of bulldozers based on their characteristics and historical sales data. By leveraging the dataset from the Kaggle Bluebook for Bulldozers competition, we aim to build a model that provides accurate price estimates, helping stakeholders make informed decisions about the value of used equipment.


## Data

The data for this project is sourced from the Kaggle Bluebook for Bulldozers competition: [Kaggle Competition - Bluebook for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers/overview)

There are three datasets:

- **Train.csv**: The training set, which contains data through the end of 2011.
- **Valid.csv**: The validation set, which contains data from January 1, 2012 - April 30, 2012. Predictions on this set are used throughout the majority of the competition to create the public leaderboard.
- **Test.csv**: The test set, which will be released in the last week of the competition. It contains data from May 1, 2012 - November 2012. The score on this set determines the final rank for the competition.

## Evaluation

The evaluation metric for this competition is the RMSLE (Root Mean Squared Logarithmic Error) between the actual and predicted auction prices.

For more information on the evaluation metric, visit: [Evaluation](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation)

## Features

Kaggle provides a data dictionary detailing all of the features of the dataset. You can view this data dictionary on Google Sheets: [Data Dictionary](https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing)

### Requirements

- Python 3.7 or higher
- Jupyter Notebook or Jupyter Lab
- Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Setup Instructions

### 1. Install Miniconda

If you don't have Miniconda installed, download and install it from the official website: [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

### 2. Clone the Repository

Clone the repository to your local machine using the following command:

```sh
git clone https://github.com/ashikaShameera/BuldozerPricePredictionModel.git
```

To run the code in this repository, follow these steps to create a virtual environment and install the required libraries:

### 3. Create a virtual environment: 
```
cd your-repo
  conda create --name myenv python=3.8
```

### 4. Active the virtual environment: 
```
conda activate myenv
```

### 5. Install the required libraries using conda:
```
conda install numpy pandas jupyter scikit-learn matplotlib
```

### 6. Run Jupyter Notebook
```
jupyter notebook
```
