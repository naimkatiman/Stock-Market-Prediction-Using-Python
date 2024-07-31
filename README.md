# Stock-Market-Prediction-using-PythonML

## Overview
This project predicts the closing prices of the S&P 500 index using machine learning techniques. By analyzing historical data, the project creates a reliable model for forecasting future stock prices based on features like Open, High, Low, Close prices, and Volume. It demonstrates data preprocessing, model training, and evaluation, providing insights into different machine learning models' performance.

## Notebooks
This repository contains two Jupyter notebooks:

1. **market_prediction.ipynb**: Initial notebook with data loading, preprocessing, and a basic linear regression model.
2. **market_prediction_updated_2024.ipynb**: Updated notebook with enhanced preprocessing, feature selection, and a RandomForestRegressor model.

## Data Source
The data used is historical data of the S&P 500 index stored in `sp500.csv`, with columns:
- Date
- Open
- High
- Low
- Close
- Volume
- NextClose

## Tech Stack
- **Languages**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib
- **Tools**: Jupyter Notebook, VS Code

## Installation Instructions
To run the notebooks and replicate the results:

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```sh
   cd <repository-directory>
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook or VS Code:
   - Jupyter Notebook:
     ```sh
     jupyter notebook
     ```
   - VS Code:
     Open the project directory in VS Code and use the Jupyter extension to run the notebooks.

5. Open and run the notebooks:
   - `market_prediction.ipynb`
   - `market_prediction_updated_2024.ipynb`

## Usage Instructions
Follow the code cells and explanations in the notebooks to understand and replicate the workflow.

## Model Description
- **Linear Regression**: Used in `market_prediction.ipynb`.
- **RandomForestRegressor**: Used in `market_prediction_updated_2024.ipynb`.

## Results
The RandomForestRegressor model has a Mean Absolute Error (MAE) of approximately 2.00, indicating high accuracy in predicting the next day's closing prices.

## Future Work
- Experiment with other machine learning models.
- Add technical indicators as features.
- Develop a web application for real-time predictions.

## Contact Information
For any questions or suggestions, contact:
- **Naim Katiman**
- Email: [naimkatiman@gmail.com](mailto:naimkatiman@gmail.com)
```

If you need any further modifications or additions, please let me know!
