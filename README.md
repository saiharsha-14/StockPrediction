# Stock Prediction System

The Stock Prediction System integrates Temporal Fusion Transformer (TFT) models and sentiment analysis to enable financial forecasting. This repository provides the necessary files and instructions to deploy an interactive web-based user interface for stock predictions, model comparisons, and trading simulations.

---

## Folder Structure

### **1. Initial_Datasets**
Contains the raw data files required for initial processing.
- `stock_index.csv`
- `posts.csv`
- `wallstreetbets_2022.csv`

### **2. Sentiment_Analysis**
Processed datasets generated after filtering and enriching raw data with sentiment scores.
- Reddit Data:
  - `tesla_reddit_data_18_to_24.csv`
  - `aapl_reddit_data_18_to_24.csv`
- News Data:
  - `tesla_news_data_18_to_24.csv`
  - `aapl_news_data_18_to_24.csv`
- Stock Data:
  - `tesla_stocks_18_to_24.csv`
  - `aapl_stocks_18_to_24.csv`

### **3. Stock_Web_UI**
Files necessary to deploy the web interface.
- **Pretrained Models**:
  - `tesla_trained_tft_model.pth`
  - `aapl_trained_tft_model.pth`
- **Sentiment-Enriched Datasets**:
  - `tsla_data_with_sentiment_analysis_from_18_to_24.csv`
  - `aapl_data_with_sentiment_analysis_from_18_to_24.csv`
- **Real-Time Data**:
  - `latest_TSLA_news_data.csv`
  - `latest_TSLA_reddit_data.csv`
  - `latest_AAPL_news_data.csv`
  - `latest_AAPL_reddit_data.csv`
- **HTML Templates**:
  - `home.html`
  - `error.html`
  - `predict.html`
  - `strategy.html`
  - `compare_models.html`

---

## Instructions

1. Clone the repository and ensure all folders are correctly structured.
2. Navigate to the `Stock_Web_UI` folder and upload the required files.
3. Open `stock_pred_UI.ipynb` in Jupyter Notebook or Google Colab.
4. Run the notebook to deploy the web interface for stock predictions.
