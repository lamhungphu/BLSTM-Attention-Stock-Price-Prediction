# BLSTM-Attention-Stock-Price-Prediction
Stock Price Prediction with BLSTM-Attention Model for 10 Companies
This repository investigates the use of a Bidirectional Long Short-Term Memory (BLSTM) network with an Attention mechanism for stock price prediction of 10 companies.

**Conceptual Approach:**

- BLSTM: Captures long-term dependencies within stock price data by processing sequences in both forward and backward directions.
- Attention Mechanism: Focuses the model's attention on crucial information within the time series data, leading to more accurate predictions.
- This implementation explores the model's performance on a diverse set of companies, potentially revealing its generalizability across different market sectors.

**What's Included:**

Jupyter Notebooks:
BiLSTM+CNN(10_Companies).ipynb.ipynb: Script for the model.
Input data Folder: Contains preprocessed stock price data for the 10 companies.

**Getting Started:**
- Download data from input file and jupyter script.
- Run Jupyter Notebooks: Open the Jupyter notebook environment and run the notebook.

**Disclaimer:**

- This is a for-educational-purposes implementation. Stock price prediction is inherently uncertain, and this model should not be used for real-world financial decisions.

**Further Exploration:**

- Experiment with hyperparameter optimization for the BLSTM and Attention mechanism.
- Explore incorporating additional features specific to each company or the broader market.
- Implement a backtesting framework to evaluate the model's performance on historical data for each company.
- Compare the performance of the BLSTM-Attention model with other architectures like CNN-LSTMs or Transformer models.

Feel free to contribute!  We welcome pull requests and suggestions for improvement.
