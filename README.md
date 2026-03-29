# real-estate-price-prediction-capstone
End-to-end exploratory data analysis and regression modeling project for residential real estate prices, including data cleaning, feature engineering, visualization of pricing drivers, and baseline-to-advanced ML models with performance comparison and interpretation.
================================================================================
CAPSTONE ASSIGNMENT 20.1 - RESULTS SUMMARY
================================================================================

[View Notebook](Capstone_20_1_EDA_Real_Estate_Price_Prediction.ipynb)

📊 RESEARCH QUESTION:
Can ML models using Zillow market data predict residential real estate prices
and identify undervalued homes?

✅ DATA ANALYZED:
  • Datasets: 14 Zillow Research CSV files
  • Geographic Scope: California metros
  • Time Period: 2020-2026
  • Total Records: 1,728
  • Focus Metro: San Jose, CA

🔍 KEY FINDINGS:
  1. Best Performing Model: Linear Regression
  2. Model Accuracy (R²): 0.9668
  3. Prediction Error (RMSE): $4,732.65
  4. Mean Absolute Error: $4,333.06
  5. Mean Absolute % Error: 0.27%

📈 MARKET INSIGHTS:
  • Average ZHVI (All Homes): $644,306.09
  • Average Days to Pending: 37.7 days
  • Average Sale-to-List Ratio: 1.003
  • Market Heat Index Range: 42.0 - 192.0

🎯 CONCLUSIONS:
  ✓ ML models successfully predict home values with high accuracy
  ✓ Ensemble methods (Random Forest, Gradient Boosting) outperform linear models
  ✓ Bedroom-specific ZHVI data provides strong predictive power
  ✓ Market dynamics (heat index, inventory, days pending) add value
  ✓ Models can identify fairly-priced homes for investors and buyers

  <img width="1390" height="790" alt="metrotrends" src="https://github.com/user-attachments/assets/523d6b81-9d58-44a2-8e78-e94061c18396" />
  <img width="1589" height="989" alt="Distributionoftrends" src="https://github.com/user-attachments/assets/e97b3b43-2409-40df-b59d-34143861074b" /><img width="1189" height="590" alt="ActualvsPredictedSanJose" src="https://github.com/user-attachments/assets/6a1680cd-344c-45e8-8d53-94b33a59a0cb" />
<img width="1099" height="1005" alt="CoRelationMatrix" src="https://github.com/user-attachments/assets/be44c921-e760-4458-8fea-0260a245fe8d" />
<img width="989" height="490" alt="ResidualPlot" src="https://github.com/user-attachments/assets/0e2769b2-4605-4260-96df-ad94df75c987" />




