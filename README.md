# SkeletonCrew
TITLE: EpiCast: Epidemic Spread Prediction with AI

EpiCast is an AI‑driven epidemic forecasting system that predicts the spread of infectious diseases using epidemiological, healthcare, and mobility data. By combining classical statistical models, machine learning, and deep learning with attention mechanisms, EpiCast delivers accurate, interpretable forecasts and visual risk maps to support proactive public health planning.

---Tech Stack---

Language: Python

Libraries: Pandas, NumPy, Scikit‑learn, Statsmodels, XGBoost, TensorFlow/Keras, Matplotlib, Seaborn, Plotly

Visualization/Dashboard: Streamlit, Dash

Version Control: GitHub

Deployment: Streamlit Cloud / Local execution

---Tools & Frameworks---

Data Handling: Pandas, NumPy

Forecasting Models: ARIMA, SARIMA, XGBoost, LSTM, Transformers with Attention

Explainability: SHAP, Attention heatmaps

Visualization: Matplotlib, Seaborn, Plotly

Dashboard: Streamlit

---Datasets---

Johns Hopkins COVID‑19 Time Series – Daily confirmed cases, deaths, recoveries.

Our World in Data COVID‑19 Dataset – Vaccination, testing, hospitalization, mortality indicators.

Google COVID‑19 Mobility Reports – Regional mobility trends and behavioral indicators.

---Features---

Forecast short‑term and medium‑term case counts.

Hotspot detection with geographic risk maps.

Integration of epidemiological, healthcare, and mobility data.

Attention‑based interpretability for deep learning models.

Interactive dashboard with forecasts, maps, and policy simulation sliders

---Technical Workflow---

Data Sources → Preprocessing → Feature Engineering → Model Training → Evaluation → Visualization → Dashboard

Data Cleaning: Handle missing values, normalize, align datasets.

Feature Engineering: Lag features, rolling averages, vaccination/testing/mobility covariates.

Modeling: ARIMA baseline → XGBoost nonlinear → LSTM + Attention → Transformer.

Evaluation: RMSE, MAE, MAPE comparison.

Visualization: Forecast curves, hotspot maps, attention heatmaps.

Dashboard: Interactive Streamlit app for forecasts and risk analysis.

---Impact---

EpiCast empowers governments and health organizations with actionable insights, enabling proactive epidemic response, resource allocation, and policy planning.











