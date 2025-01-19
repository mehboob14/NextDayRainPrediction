Nextday Rain Predictions

This repository contains the implementation of a Data Science course project focused on rain prediction using the Netday Rain Predictions dataset sourced from Kaggle. The project includes data preprocessing, handling class imbalance, model implementation, and evaluation.
Table of Contents

    Overview
    Dataset
    Technologies Used
    Project Workflow
    Installation and Setup
    Usage
    Results
    Contributing
    License

Overview

The project demonstrates the end-to-end data science pipeline, from data preprocessing to model evaluation. Various techniques were applied to improve prediction accuracy, including:

    Data preprocessing
    Addressing class imbalance
    Feature engineering
    Model training and evaluation

Models explored:

    Logistic Regression
    Random Forest

Dataset

The dataset used for this project is the Netday Rain Predictions dataset, which is available on Kaggle. It includes features that help predict rain events based on historical weather data.
Files in this Repository:

    *.ipynb: Jupyter notebooks containing the step-by-step implementation of the project.
    *.csv: Dataset files used in this project.

Technologies Used

    Python: Core programming language
    Pandas: For data manipulation and analysis
    NumPy: For numerical computations
    Scikit-learn: For implementing machine learning models
    Matplotlib/Seaborn: For data visualization
    Jupyter Notebook: For interactive development

Project Workflow

The workflow of this project includes:

    Data Preprocessing
        Handling missing values
        Encoding categorical features
        Scaling numerical features
    Class Imbalance
        Techniques such as oversampling and undersampling were used.
    Feature Selection
        Correlation analysis and feature importance methods.
    Model Training
        Logistic Regression
        Random Forest
    Model Evaluation
        Metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Installation and Setup

    Clone the repository:

git clone https://github.com/your-repo/netday-rain-predictions.git
cd netday-rain-predictions

Create a virtual environment (optional but recommended):

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

Install the required dependencies:

pip install -r requirements.txt

Launch the Jupyter Notebook:

    jupyter notebook

Usage

    Open the Jupyter notebooks to view the step-by-step implementation.
    Place the dataset files (*.csv) in the same directory as the notebooks or update the file paths in the code.
    Run each cell sequentially to reproduce the results.

Results

    The Random Forest model outperformed Logistic Regression in terms of accuracy and precision.
    Key metrics:
        Accuracy: 85%
        Precision: 82%
        Recall: 79%
        ROC-AUC: 88%

Contributing

If you'd like to contribute to this project, feel free to submit a pull request. For major changes, please open an issue first to discuss the changes.
License

This project is licensed under the MIT License. See the LICENSE file for details.
