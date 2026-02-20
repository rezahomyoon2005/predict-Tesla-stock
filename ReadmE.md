# 📉 Tesla Stock Price Prediction using LSTM



## 🚀 Project Overview
The goal of this project is to build a robust time-series forecasting model. By analyzing the last 60 days of "Close" prices, the model attempts to predict the price for the next trading day.

### 🛠 Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook / Kaggle / Google Colab
* **Libraries:** * `yfinance`: For fetching real-time stock data.
    * `numpy` & `pandas`: For data manipulation.
    * `scikit-learn`: For data scaling (MinMaxScaler).
    * `tensorflow.keras`: For building and training the LSTM neural network.
    * `matplotlib`: For high-quality result visualization.

---

## 📂 Notebook Structure
The notebook is organized into logical steps to ensure reproducibility:

1.  **Data Acquisition:** Downloading historical TSLA data via Yahoo Finance API.
2.  **Feature Engineering:** Extracting the 'Close' price and creating a 60-day sliding window dataset.
3.  **Data Preprocessing:** Normalizing data to a range of [0, 1] to optimize neural network performance.
4.  **Model Architecture:** * Input Layer (LSTM)
    * Hidden Layers (LSTM/Dense)
    * Output Layer (Dense)
5.  **Training:** Fitting the model on historical training data.
6.  **Evaluation:** Visualizing the "Actual vs. Predicted" prices on the test set.

---

## 📊 Results
The model demonstrates a strong ability to follow market trends. As seen in the generated plots, the predicted price (red) closely tracks the actual price (white), capturing major market pivots with minimal lag.

---



## 📝 How to Use
1. Clone this repository.
2. Install dependencies: `pip install yfinance tensorflow matplotlib pandas numpy scikit-learn`.
3. Open `notebook688c78d5e0.ipynb` in Jupyter or Kaggle.
4. Run all cells to see the live data fetch and prediction results.

---

