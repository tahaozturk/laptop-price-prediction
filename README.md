# Laptop Price Prediction Model

## Project Overview
This project develops a model to predict laptop prices based on various features. Utilizing a detailed preprocessing approach, the model handles both categorical and continuous variables through encoding and feature engineering. The dataset includes features such as RAM, weight, CPU clock speed, and more. A Random Forest Regressor is employed for the prediction task, with performance evaluated using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.

## Features
- Comprehensive data preprocessing and cleaning.
- Feature engineering for complex features such as 'Memory', 'ScreenResolution', and 'Cpu'.
- Price prediction using Random Forest Regression.
- Evaluation using MSE, RMSE, and R-squared metrics.

## Requirements
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Installation
1. Clone this repository:
git clone https://github.com/tahaozturk/laptop-price-prediction.git

2. Navigate to the project directory:
cd laptop-price-prediction

3. Install required dependencies:
pip install -r requirements.txt

## Usage
Run the `laptop_price_prediction.ipynb` notebook in Jupyter Notebook to train the model and make predictions.

## Data
The `laptop_price.csv` dataset, which includes a variety of laptop features, is used for training. The model undergoes detailed preprocessing to prepare data for modeling, addressing both continuous and categorical features.

## Model Performance
The model's accuracy is assessed using MSE, RMSE, and R-squared metrics. Cross-validation scores are provided to evaluate the model's generalizability.

## Contributing
Contributions to enhance the model or expand the dataset are welcome. Please fork the repository and submit a pull request with your improvements.

## License
This project is available under the MIT License - see the LICENSE.md file for details.

