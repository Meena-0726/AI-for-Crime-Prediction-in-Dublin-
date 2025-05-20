# AI-for-Crime-Prediction-in-Dublin-

🧠 AI for Crime Prediction in Dublin
📍 Project Type: Machine Learning / Time-Series Forecasting
📁 Domain: Crime Data Analytics
📍 Location: Dublin, Ireland
📅 Timeline: 2025
🧑‍🎓 Author: Lakshmi Meena Manivannan

📌 Table of Contents
📖 About the Project

🧰 Tools and Technologies Used

📂 Folder Structure

📊 Exploratory Data Analysis

🧠 Models Implemented

📈 Model Evaluation

🔍 Key Insights

⚠️ Limitations

🚀 Future Enhancements

🙋‍♀️ About Me

📖 About the Project
This project applies AI and machine learning techniques to predict crime trends in Dublin using historical data. It involves data cleaning, feature engineering, time-series forecasting, model comparison, and visual storytelling to assist urban safety planning and public policy.

🔍 Objective: Build a predictive system using ARIMA, LSTM, and Random Forest to forecast future crime occurrences for proactive law enforcement.

🧰 Tools and Technologies Used
Category	Tools/Libraries
Language	Python
IDE	Jupyter Notebook
Data Handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn, Plotly
Machine Learning	Scikit-learn, TensorFlow, Keras
Time-Series	Statsmodels (ARIMA), LSTM

📂 Folder Structure
bash
Copy
Edit
├── data/                # Dataset files
├── notebooks/           # Jupyter Notebooks for each model
├── models/              # Trained model outputs
├── visualizations/      # Graphs and dashboards
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
📊 Exploratory Data Analysis
📈 Time Series Trends: Seasonality and monthly spikes identified

📅 Crime by Day/Month/Quarter: Weekends and Q3/Q4 have higher crimes

🗺️ Top Regions: Dublin Metropolitan and Cork City rank highest

🔥 Correlation Heatmap: Strongest link found with Type of Offence

📋 Top Crime Categories: Theft and Public Order Offences dominate

🧠 Models Implemented
🔹 ARIMA
📊 Traditional time-series model

Best for linear trends & seasonality

Simple, interpretable, and fast

🔹 LSTM (Long Short-Term Memory)
🤖 Deep learning model for sequential prediction

Captures both short-term volatility and long-term dependencies

✅ Best performing model

🔹 Random Forest Regressor
🌳 Feature-based ensemble model

Learns from engineered time features (e.g. month, day, year)

Offers feature importance insights for decision-making

📈 Model Evaluation
Metric	ARIMA	LSTM	Random Forest
MAE	Moderate	✅ Lowest	Higher
RMSE	Moderate	✅ Lowest	Higher
R² Score	Medium	✅ Highest	Lower

✅ LSTM was statistically superior (paired t-tests confirmed)

📉 Visual inspection confirmed LSTM matched trends closest

🔍 Key Insights
LSTM handled irregular crime spikes better than ARIMA and RF

Random Forest was interpretable, highlighting important time features

ARIMA performed well on regular, cyclical data, but missed anomalies

📊 Time Series Decomposition supported the presence of seasonality

🏙️ Dublin consistently had higher crime rates than other regions

⚠️ Limitations
❌ Real-time prediction dashboard not included

❌ Spatial mapping of crime hotspots was planned but not implemented

🚀 Future Enhancements
🧭 Add geospatial analysis for crime hotspot prediction

⚡ Build real-time dashboards for live predictions

🧠 Implement Explainable AI (SHAP, LIME) for transparency

🌍 Generalize models to other cities/countries

🤝 Ensemble models for improved robustness

🙋‍♀️ About Me
👩‍💻 Lakshmi Meena Manivannan
🎓 MSc Data Analytics — National College of Ireland
📧 Email: x23426918@student.ncirl.ie
📍 Dublin, Ireland


