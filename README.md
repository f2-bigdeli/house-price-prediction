# House Sales Price Prediction

This project aims to predict the sales price of houses using various supervised learning models. The dataset includes features such as the type of dwelling, lot configuration, neighborhood, house style, and other relevant factors. The objective is to predict the sale price for each house in the test dataset.

## Project Structure

- `train.csv`: Training dataset containing features and target labels (SalePrice).
- `test.csv`: Test dataset for making predictions.
- `data_description.txt`: Detailed description of the dataset features.
- `test_predictions.csv`: Predicted sale prices for the test dataset.
- `Supervised_Learning_Models.ipynb`: Jupyter notebook containing the data preprocessing, model training, evaluation, and prediction code.

## Models Used

The following supervised learning models were used and evaluated in this project:
- Linear Regression
- Random Forest
- Gradient Boosting

## Evaluation Metrics

The models were evaluated using cross-validation with the following metric:
- Root Mean Squared Error (RMSE)

## Results

The model with the lowest mean RMSE from cross-validation was selected as the best model. This model was then used to make predictions on the test dataset.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/f2-bigdeli/house-price-prediction.git
   cd house-price-prediction
