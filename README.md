# Retail Intelligence & AI-Powered Sales Forecasting

## Project Overview
This project is an end-to-end data science solution designed to optimize retail operations. It transforms 73,000+ raw transactions into a strategic decision-making engine using a dual-layered AI approach: identifying high-value store segments and forecasting revenue trends.

## Technical Stack
*   **Analytics Engine:** Python (Pandas, Scikit-Learn, XGBoost)
*   **Business Intelligence:** Power BI (Interactive Executive Dashboards)
*   **Clustering:** K-Means for Store Tiering
*   **Forecasting:** XGBoost Regression

## Key Business Insights
*   **The Promo Paradox:** Statistical T-Testing revealed a p-value of **0.68**, proving that broad promotions were not significantly driving revenue lift—leading to a recommendation to pivot to Tier-specific premium experiences.
*   **Predictive Accuracy:** The XGBoost model achieved a **Mean Absolute Error (MAE) of $4,718**, providing a high-confidence window for inventory and labor scheduling.
*   **Strategic Segmentation:** Successfully clustered 100+ locations into **Flagship (Tier 1)**, **Growth (Tier 2)**, and **Value (Tier 3)** stores for targeted marketing spend.

## Repository Contents
*   `Retail_Forecasting_Engine.ipynb`: Full Python pipeline for cleaning, clustering, and modeling.
*   `Retail_Intelligence_Dashboard.pbix`: Interactive Power BI report (Requires Power BI Desktop).
*   `Final_Enterprise_Master_Data.csv`: The "Golden Dataset" engineered for the final model.
*   `Executive_Summary.pdf`: Formal business case and strategic recommendations.

## How to Use
1. **Model:** Run the Jupyter Notebook to see the data engineering and model validation steps.
2. **Dashboard:** Open the `.pbix` file to interact with the revenue heatmaps and price elasticity charts.
