# GlucoTwin-India
Project pitch: GlucoTwin India creates a virtual model of an individual using historical health records and continuously updated wearable or simulated sensor data. It analyzes trends in glucose, activity, sleep and other relevant indicators to estimate the likelihood of a glucose excursion, explain contributing factors and provide a clinician-facing monitoring dashboard.

Why this fits the challenge: The concept targets one chronic condition, combines two required data streams, supports an explicit prediction task, and demonstrates how a doctor could interact with the patient’s digital twin. 


3. Suggested technical architecture
Historical health records
Synthetic patient profile, past diagnoses, laboratory results
Dynamic sensor stream
Simulated glucose, heart rate, sleep and activity time series
Data processing and feature engineering
Time alignment, missing-value handling, rolling-window features
Prediction model
Baseline model followed by a validated time-series or tree-based model
