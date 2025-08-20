# 5656745_Dissertation

## Project Description
This project addresses the critical challenge of enhancing supply chain resilience by enabling proactive risk mitigation. It implements an integrated AI-driven framework that predicts transportation and logistics delays in land-based networks using advanced machine learning models. A key innovation lies in translating these complex predictive outputs into clear, actionable, and interpretable risk assessments via a dynamic scorecard, bridging the gap between AI sophistication and managerial utility. The framework emphasizes robust data engineering, temporal validation, and Explainable AI (XAI) principles.

## Key Files
*   `dissertation_main_script.py`: The main Python script that executes the full AI-driven framework, from data understanding and preparation to model training, evaluation, and scorecard generation.
*   `supply_chain_risk_dataset.csv`: The primary input dataset used for this study. *Please note: This dataset was originally sourced from Kaggle. For direct replication, you may need to download it from its original public source if a local copy is not included.*
*   `final_scorecard_data.xlsx`: The final Excel-based Risk Assessment Scorecard, containing detailed per-shipment risk insights and aggregated data for strategic analysis.
*   `requirements.txt`: A list of all Python library dependencies required to run the project.
*   `models/`: (Directory) Contains the saved trained machine learning models (`.pkl` for Logistic Regression and XGBoost, `.h5` for LSTM).
*   `processed_data/`: (Directory) Contains intermediate `.pkl` files for processed data splits (`X_train_processed.pkl`, etc.).
