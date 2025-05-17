Nebula Finance Lab
 
A multi-themed Streamlit application for financial machine learning analysis, developed for the AF3005 – Group Project at [University Name]. The app fetches real-time stock data from Yahoo Finance, supports Kaggle dataset uploads, and applies machine learning models with unique visual themes.
🎯 Project Overview
Nebula Finance Lab is an interactive web application built with Streamlit that enables users to analyze financial datasets using machine learning. It supports real-time stock data fetching via the Yahoo Finance API and CSV/Excel uploads (e.g., Kaggle datasets). Each team member implemented a distinct visual theme, seamlessly integrated into a single app with four machine learning models.
Team Members

Muhammad Arsalan: Designed the Zombie Theme with Linear Regression (Returns feature).
Tallal Zubair: Developed the Futuristic Theme with Logistic Regression (RSI feature).
Muhammad Hassaan Asif: Created the Game of Thrones Theme with K-Means Clustering (Moving Average feature).
Team Collaboration: All members collaborated on the Nebula Pulse Theme with XGBoost (Returns feature) and integrated the app.

🚀 Features

Data Sources:
Fetch real-time stock data using yfinance (e.g., AAPL, MSFT).
Upload financial datasets (CSV/Excel) from Kaggle or other sources.


Machine Learning Models:
Linear Regression (Zombie Theme)
Logistic Regression (Futuristic Theme)
K-Means Clustering (Game of Thrones Theme)
XGBoost (Nebula Pulse Theme)


Visual Themes:
Zombie Theme: Dark, eerie colors with horror GIFs and Creepster font.
Futuristic Theme: Neon blues with space animations and Exo 2 font.
Game of Thrones Theme: Medieval golds with fire/ice GIFs and Cinzel font.
Nebula Pulse Theme: Vibrant purples with gaming GIFs and Poppins font.


Interactivity:
Dynamic theme switching via sidebar.
Interactive buttons (Fetch Data, Refresh, Clear Cache, Train Model).
Visualizations with Plotly and Matplotlib (trends, predictions, statistics).
Downloadable model results as CSV.


Error Handling:
Robust retries and period fallback for Yahoo Finance API.
Clear user guidance for invalid inputs or API failures.



📸 Screenshots



Welcome Page
Dashboard
Analysis








Replace placeholders with actual screenshots from your deployed app.
🛠 Installation
Prerequisites

Python 3.8+
Git

Steps

Clone the repository:git clone https://github.com/yourusername/AF3005-Nebula-Finance-Lab.git
cd AF3005-Nebula-Finance-Lab


Install dependencies:pip install -r requirements.txt


Run the app locally:streamlit run app.py



Requirements
See requirements.txt for details:
streamlit>=1.24.0
pandas>=1.5.0
numpy>=1.21.0
yfinance>=0.2.0
scikit-learn>=1.0.0
plotly>=5.13.0
ta>=0.10.0
xgboost>=1.7.0
openpyxl>=3.0.0
matplotlib>=3.5.0

🚀 Usage

Launch the App:
Run streamlit run app.py or visit the deployed app (update with Streamlit Cloud URL).


Load Data:
Yahoo Finance: Enter a ticker (e.g., AAPL) and select a period (e.g., 1y).
Upload File: Upload a CSV/Excel file with columns Date, Open, High, Low, Close, Volume.


Explore Themes:
Switch between Zombie, Futuristic, Game of Thrones, and Nebula Pulse themes via the sidebar.


Analyze Data:
View data trends and statistics in the Dashboard tab.
Train and evaluate ML models in the Analysis tab.


Download Results:
Export model predictions as a CSV file.



🌐 Deployment
The app is deployed on Streamlit Cloud at: [Insert Streamlit URL Here]
To deploy yourself:

Push the repository to GitHub.
Sign in to Streamlit Cloud with GitHub.
Create a new app, selecting:
Repository: yourusername/AF3005-Nebula-Finance-Lab
Branch: main
Main File Path: app.py


Deploy and share the URL.

📝 Project Details

Course: AF3005 – Financial Machine Learning
Instructor: Dr. Usama Arshad
Batch: BSFT 22, Sections A, B, C
Submission Date: May 17, 2025
Objective: Build a multi-themed Streamlit app for financial ML analysis.

🤝 Contributions

Muhammad Arsalan: Implemented Zombie Theme, Linear Regression, and coordinated app integration.
Tallal Zubair: Developed Futuristic Theme, Logistic Regression, and enhanced error handling.
Muhammad Hassaan Asif: Created Game of Thrones Theme, K-Means Clustering, and tested visualizations.
Team: Collaborated on Nebula Pulse Theme, XGBoost, UI design, and deployment.

📌 LinkedIn Posts

Muhammad Arsalan: [Insert LinkedIn Post URL]
Tallal Zubair: [Insert LinkedIn Post URL]
Muhammad Hassaan Asif: [Insert LinkedIn Post URL]

Update with actual LinkedIn post links after posting.
📚 References

Streamlit Documentation
Yahoo Finance API (yfinance)
Kaggle Financial Datasets
Scikit-learn
Plotly

📜 License
This project is licensed under the MIT License. See LICENSE for details.

Nebula Finance Lab © 2025Developed with 💻 and ☕ by Muhammad Arsalan, Tallal Zubair, and Muhammad Hassaan Asif.
