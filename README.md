# Bitcoin Price Detection

## Introduction

This project aims to predict the future price of Bitcoin using historical data on the price of Bitcoin, along with data from Wikipedia about edits to the Bitcoin page. The project will use two Jupyter notebooks:

- prediction.ipynb - This notebook contains the code to predict Bitcoin prices. It will merge and combine the historical data and Wikipedia edit data, then use it to train a random forest model that will tell us if Bitcoin prices will increase or decrease tomorrow. The notebook will then switch to an XGBoost model and better predictors to improve accuracy.

- sentiment.ipynb - This notebook creates the Wikipedia edit dataset. It will extract data from Wikipedia about edits to the Bitcoin page, and then store this data in a format that can be used by the prediction notebook.
The project will also develop a backtesting system and use a robust error metric so we can tell if the algorithm is performing well. The project can be extended to other cryptocurrencies as well.

## Benefits

This project has the potential to provide several benefits, including:

- A better understanding of the factors that influence the price of Bitcoin.
- More informed decisions about when to buy or sell Bitcoin.
- Better strategies for trading Bitcoin.
  
## Requirements

To run this project, you will need the following:

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- XGBoost


**Thank you for your interest in this project!**
