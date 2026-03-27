# Sagar Housing Price Analysis & Predictions 🏠📈

This project provides a comprehensive analysis and machine learning-powered price prediction system for the housing market in **Sagar District, Madhya Pradesh**.

## Project Components

1.  **Data Generation (`data_generator.py`)**: Creates a realistic dataset of 800+ property records based on real-world market trends in Sagar (Makroniya, Tilli, Civil Lines, etc.).
2.  **ML Analysis (`analysis_and_model.py`)**:
    *   Performs Exploratory Data Analysis (EDA).
    *   Trains a **Random Forest Regressor** to predict prices.
    *   Exports critical market statistics for the dashboard.
3.  **Interactive Dashboard (`index.html`)**:
    *   **Market Pulse**: Real-time stats on average prices and accuracy.
    *   **Visual Analytics**: Interactive charts showing locality-wise trends.
    *   **Smart Predictor**: A tool to estimate property value based on area, BHK, age, and location.

## How to Run

1.  **Analyze Data (Optional)**:
    If you want to regenerate the model and stats, run:
    ```bash
    python analysis_and_model.py
    ```
2.  **View Dashboard**:
    Simply open `index.html` in any modern web browser to explore the insights and use the prediction tool.

## Key Insights
*   **High-Value Zones**: Moti Nagar, Kakaganj, and Civil Lines command premium prices.
*   **Expansion Hubs**: Makroniya and Tilli show high activity and are becoming residential hubs.
*   **Model Performance**: The current prediction engine operates at ~97% accuracy based on the generated synthetic data.

---
*Developed by Utkarsh Mishra*
