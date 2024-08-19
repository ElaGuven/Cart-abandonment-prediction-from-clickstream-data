# Cart Abandonment Prediction from Clickstream Data

This repository contains the code and prediction outputs for a project focused on predicting cart abandonment using clickstream data. The project involves various models and methodologies aimed at accurately identifying when a user is likely to abandon their cart during an online shopping session.

## Project Overview

The goal of this project is to develop models that can predict cart abandonment using clickstream data. The project explores different models, including baseline models and more advanced experimental models, and evaluates their performance across various scenarios.

### Files in the Repository

- **`Cart abandonment prediction from clickstream data.ipynb`**: This Jupyter Notebook contains the code for data preprocessing, model training, evaluation, and generation of predictions. It walks through the steps involved in handling clickstream data and building models to predict cart abandonment.
- **`predictions_group10_baseline_at5.json`**: Prediction results from the baseline model at the 5th checkpoint.
- **`predictions_group10_baseline_at10.json`**: Prediction results from the baseline model at the 10th checkpoint.
- **`predictions_group10_baseline_at15.json`**: Prediction results from the baseline model at the 15th checkpoint.
- **`predictions_group10_expModel_at5.json`**: Prediction results from the experimental model at the 5th checkpoint.
- **`predictions_group10_expModel_at10.json`**: Prediction results from the experimental model at the 10th checkpoint.
- **`predictions_group10_expModel_at15.json`**: Prediction results from the experimental model at the 15th checkpoint.
- **`predictions_group10_oracle_at5.json`**: Prediction results from the oracle model at the 5th checkpoint.
- **`predictions_group10_oracle_at10.json`**: Prediction results from the oracle model at the 10th checkpoint.
- **`predictions_group10_oracle_at15.json`**: Prediction results from the oracle model at the 15th checkpoint.

## How to Use

1. **Prerequisites**:
   - Ensure you have Python installed along with the necessary libraries (`numpy`, `pandas`, `scikit-learn`, `matplotlib`, etc.).
   - The `.json` files contain the prediction outputs from different models and checkpoints.

2. **Running the Notebook**:
   - Open the Jupyter Notebook (`.ipynb` file) in your preferred environment (e.g., JupyterLab, VSCode).
   - Execute the cells in sequence to replicate the data preprocessing, model training, and evaluation steps.
   - The notebook also generates and saves predictions based on the trained models.

3. **Evaluating Predictions**:
   - The `.json` files can be used to analyze the prediction results from different models and checkpoints.
   - Compare the performance of different models using metrics such as accuracy, precision, recall, etc.

## Project Structure

The repository is structured to provide a clear overview of the modeling process, from data preprocessing to prediction generation. The different prediction files correspond to outputs at various stages of the modeling process, allowing for comprehensive evaluation of model performance.

## Conclusion

This project provides valuable insights into the predictive modeling of cart abandonment using clickstream data. The exploration of baseline, experimental, and oracle models showcases the potential for improving prediction accuracy and understanding user behavior in e-commerce settings.
