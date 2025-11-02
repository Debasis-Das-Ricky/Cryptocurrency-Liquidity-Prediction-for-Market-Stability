Cryptocurrency Liquidity Prediction for Market Stability
A comprehensive machine learning project to forecast cryptocurrency liquidity levels using real CoinGecko data. This project enables early detection of market instability, helping traders and exchanges manage risks and make informed decisions.

🚀 Project Overview
Cryptocurrency markets are characterized by high volatility, where liquidity is crucial for stable trading environments. This project leverages Python and machine learning to predict liquidity levels for top cryptocurrencies by analyzing multiple market factors, including price, trading volume, market capitalization, and price movement trends.

Key Objectives:
  Detect potential liquidity crises early
  Forecast liquidity fluctuations for informed risk management
  Visualize, analyze, and interpret market liquidity patterns

📦 Project Features:
  Real Data: Uses CoinGecko CSV snapshots for 2022-03-16 and 2022-03-17
  Comprehensive EDA: Statistical and graphical analysis of price, volume, and liquidity patterns
  Feature Engineering: Construction of 11+ liquidity indicators including price momentum, volatility, and volume-to-market-cap ratio
  Model Training: Multiple ML models (Linear Regression, Random Forest, Gradient Boosting, XGBoost)
  Model Evaluation: In-depth comparison using RMSE, MAE, and R² metrics plus feature importance analysis
  Prediction & Reporting: Generates predictions, analyzes error, and provides professional reporting for decision making
  Production Ready: Modular code and ready-to-export results for real-world adaptation

📁 Repository Structure:

  cryptocurrency-liquidity-prediction/
├── notebooks/
│   └── Cryptocurrency_Liquidity_Prediction.ipynb
├── data/
│   ├── coin_gecko_2022-03-16.csv
│   └── coin_gecko_2022-03-17.csv
├── results/
│   ├── model_evaluation_results.csv
│   ├── predictions.csv
│   ├── processed_features.csv
│   └── feature_importance.csv
├── reports/
│   ├── Project_Summary_Report.txt
│   ├── EDA_Report.md
│   ├── HLD_Document.md
│   └── LLD_Document.md
├── models/
│   └── best_model.pkl
└── README.md


🛠️ Technologies Used
   Python (pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, plotly)
   Google Colab for interactive development and analysis
   CoinGecko API data in CSV format

📝 How to Use
   Clone the repository and upload the provided notebook and CSV files into Google Colab.
   Run the notebook cells sequentially following the provided documentation.
   Review results, export findings, and adapt models as needed for production or research use.



