# Predict-Bike-Sharing-Demand-with-AutoGloun

## Project Overview

This project aims to predict bike-sharing demand using AutoGluon, an open-source AutoML toolkit. The notebook provided in this repository is a template that guides you through each step required to complete the project.

## Table of Contents

- [Project Overview](#project-overview)
- [Step 1: Create an account with Kaggle](#step-1-create-an-account-with-kaggle)
- [Step 2: Download the Kaggle dataset using the Kaggle Python library](#step-2-download-the-kaggle-dataset-using-the-kaggle-python-library)
- [Step 3: Train a model using AutoGluon’s Tabular Prediction](#step-3-train-a-model-using-autogluon’s-tabular-prediction)
- [Step 4: Exploratory Data Analysis and Creating an additional feature](#step-4-exploratory-data-analysis-and-creating-an-additional-feature)
- [Step 5: Rerun the model with the same settings as before, just with more features](#step-5-rerun-the-model-with-the-same-settings-as-before-just-with-more-features)
- [Step 6: Hyperparameter optimization](#step-6-hyperparameter-optimization)
- [Step 7: Write a Report](#step-7-write-a-report)

## Step 1: Create an account with Kaggle

1. Open account settings on Kaggle.
2. Scroll down to API and click 'Create New API Token'.
3. Download the `kaggle.json` file containing your username and API key.

## Step 2: Download the Kaggle dataset using the Kaggle Python library

1. Open Sagemaker Studio and use the starter template.
2. Ensure the notebook is using a `ml.t3.medium` instance and the `Python 3 (MXNet 1.8 Python 3.7 CPU Optimized)` kernel.
3. Install the required packages using pip.
4. Set up the Kaggle API key by creating a `.kaggle` directory and placing the `kaggle.json` file in it.
5. Download and unzip the bike-sharing demand dataset from Kaggle.

## Step 3: Train a model using AutoGluon’s Tabular Prediction

1. Prepare the training and test datasets by parsing the datetime column.
2. Train the model using AutoGluon's TabularPredictor, focusing on predicting the `count` label.
3. Review the training run and evaluate the model's performance using the `root_mean_squared_error` metric.
4. Generate predictions on the test dataset and ensure all predictions are non-negative.
5. Submit the predictions to the Kaggle competition.

## Step 4: Exploratory Data Analysis and Creating an additional feature

1. Create histograms for all features to analyze their distributions.
2. Create new features by extracting year, month, and day from the datetime column.
3. Convert categorical features to the appropriate data types for better model performance.

## Step 5: Rerun the model with the same settings as before, just with more features

1. Train the model again with the new features added in Step 4.
2. Review the training run and evaluate the model's performance.
3. Generate predictions on the test dataset, ensuring all predictions are non-negative.
4. Submit the new predictions to the Kaggle competition.

## Step 6: Hyperparameter optimization

1. Train a new model with hyperparameter optimization using AutoGluon's TabularPredictor.
2. Review the training run and evaluate the model's performance.
3. Generate predictions on the test dataset, ensuring all predictions are non-negative.
4. Submit the new predictions with optimized hyperparameters to the Kaggle competition.

## Step 7: Write a Report

1. Create plots and tables to summarize the model's performance and improvements.
2. Document the results and findings in a markdown or PDF report.
3. Include charts, such as line plots showing model improvement, and tables summarizing hyperparameter tuning results.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or bug fixes. All contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

