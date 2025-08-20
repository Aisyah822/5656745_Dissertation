# 5656745_Dissertation

## Project Description
This project addresses the critical challenge of enhancing supply chain resilience by enabling proactive risk mitigation. It implements an integrated AI-driven framework that predicts transportation and logistics delays in land-based networks using advanced machine learning models. A key innovation lies in translating these complex predictive outputs into clear, actionable, and interpretable risk assessments via a dynamic scorecard, bridging the gap between AI sophistication and managerial utility. The framework emphasizes robust data engineering, temporal validation, and Explainable AI (XAI) principles.

## Key Files
*   `dissertation_main_script.py`: The main Python script that executes the full AI-driven framework, from data understanding and preparation to model training, evaluation, and scorecard generation.
*   `supply_chain_risk_dataset.csv`: The main input dataset used for this study. *Please note: This dataset was originally sourced from Kaggle. For successful execution, ensure this file is uploaded to your Google Colab environment or mounted from Google Drive as instructed in the notebook.*
*   `final_scorecard_data.xlsx`: The final Excel-based Risk Assessment Scorecard, containing detailed per-shipment risk insights and aggregated data for strategic analysis.

**Important Note on LSTM Output Variability:**
The LSTM classifier, particularly for delay probability (`predicted_probability_of_delay`), generates continuous probability scores. While the overall model performance metrics (e.g., Recall, F1-score, AUC) are consistent and robust, slight numerical variations in the *exact probability outputs* may be observed upon re-running the model. This is due to the inherent stochastic nature of neural network training, which can be influenced by factors such as random initialization, floating-point precision, and specific hardware/software configurations. However, these minor numerical differences do not impact the qualitative insights, the overall classification performance, or the framework's practical utility.
