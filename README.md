# AI-for-Crime-Prediction-in-Dublin-

🧠 AI for Crime Prediction in Dublin
📍 Project Overview
This project uses Artificial Intelligence and Machine Learning techniques to predict future crime trends in Dublin, Ireland. It leverages historical crime data, performs comprehensive time-series and classification modeling, and compares the performance of ARIMA, LSTM, and Random Forest algorithms. The goal is to build a robust and scalable crime forecasting model that can assist law enforcement and policymakers in making data-driven decisions to enhance urban safety.

🗃 Dataset
The dataset was obtained from open data portals such as Kaggle and includes:

Dates: Timestamp of crime occurrence

Category: Crime type (e.g., theft, assault)

PdDistrict: Police district (not used for geospatial analysis here)

DayOfWeek: To identify weekly patterns

Address: Stored for potential future geospatial use

🔍 Why This Dataset?
Clean and well-labeled

Covers multiple years (ideal for time-series forecasting)

Publicly accessible

Standardized timestamp and category features

🔧 Tools and Technologies Used
Tool	Purpose
Python	Core programming language
Jupyter Notebook	Development environment
Pandas & NumPy	Data preprocessing and manipulation
Matplotlib & Seaborn	Static data visualization
Plotly	Interactive dashboards
Scikit-learn	Feature engineering, ML models
Statsmodels	ARIMA model
TensorFlow/Keras	Deep learning (LSTM)

🧪 Machine Learning Models
1. ARIMA (AutoRegressive Integrated Moving Average)
Captures linear crime trends and seasonality

Great for baseline time-series forecasting

2. LSTM (Long Short-Term Memory)
Deep learning model capable of learning complex temporal patterns

Best performing model in terms of accuracy

3. Random Forest Regressor
Feature-based ensemble learning model

Highlights importance of engineered temporal features

📈 Model Evaluation Metrics
MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score (Coefficient of Determination)

MSE (Mean Squared Error)

✅ LSTM achieved the best results with lowest MAE/RMSE and highest R².

📊 Visualizations & Insights
📉 Time series plots showing monthly crime patterns

📊 Bar charts for top Garda regions and crime types

🌍 Animated map visualizing changes in crime regions

🔥 Heatmap for feature correlation

📈 Actual vs Predicted plots for model comparison

📌 Key Findings
LSTM had the most accurate and consistent predictions

Random Forest offered good short-term insights and feature importance

ARIMA worked well for seasonal patterns but not for volatile spikes

Statistical tests (t-test) confirmed LSTM’s superior performance was significant

❗ Limitations
Real-time dashboard not implemented

Crime hotspot mapping excluded due to time constraints

🔮 Future Work
Add geospatial analysis for hotspot detection

Build real-time streaming prediction dashboards

Use SHAP/LIME for explainability

Expand model to other cities or regions

Test ensemble models for improved accuracy

📁 Folder Structure
bash
Copy
Edit
├── data/                # Raw dataset files
├── notebooks/           # Jupyter notebooks for each model
├── models/              # Trained models
├── visualizations/      # Plots and graphs
├── README.md
└── requirements.txt     # Python dependencies
🙋‍♀️ Author
Lakshmi Meena Manivannan
📧 x23426918@student.ncirl.ie
🎓 MSc Data Analytics, National College of Ireland

📄 License
This project is licensed for academic and research purposes only.
Dataset sources are publicly available and credited accordingly.
