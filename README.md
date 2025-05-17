Nebula Finance Lab



Nebula Finance Lab is a multi-themed Streamlit application developed for the AF3005 Group Project (BSFT Batch 22, Sections A, B, C) at [Your University Name]. This interactive app fetches real-time stock market data from Yahoo Finance, supports Kaggle dataset uploads, and applies machine learning models to analyze financial data. Each team member contributed a unique visual theme with a distinct ML model, creating an engaging and cohesive user experience.

🎯 Project Objective

The project aims to collaboratively design and develop a creative, interactive financial machine learning application using Streamlit. It integrates real-time data, Kaggle datasets, and four machine learning models, each presented with a unique visual theme crafted by a team member.

🛠️ Features





Data Sources:





Fetch real-time stock data using Yahoo Finance API (yfinance).



Upload financial datasets (CSV/Excel) from Kaggle or other sources.



Machine Learning Models:





Linear Regression (Zombie Theme)



Logistic Regression (Futuristic Theme)



K-Means Clustering (Game of Thrones Theme)



XGBoost (Nebula Pulse Theme)



Visual Themes:





Zombie Theme: Dark, eerie aesthetics with horror GIFs and Creepster font.



Futuristic Theme: Neon colors, space animations, and Exo 2 font.



Game of Thrones Theme: Medieval style with fire/ice GIFs and Cinzel font.



Nebula Pulse Theme: Vibrant gaming vibes with pixel art GIFs and Poppins font.



Interactivity:





Dynamic theme switching, interactive charts (Plotly, Matplotlib), buttons for data fetching and model training, and cache management.



Error handling with user-friendly notifications and suggestions.

👥 Team Members & Contributions







Member Name



Contribution



Theme



ML Model





[Member 1 Name]



Designed Zombie Theme, implemented Linear Regression, and handled data fetching



Zombie



Linear Regression





[Member 2 Name]



Developed Futuristic Theme, implemented Logistic Regression, and added RSI feature



Futuristic



Logistic Regression





[Member 3 Name]



Created Game of Thrones Theme, implemented K-Means Clustering, and managed UI styling



Game of Thrones



K-Means Clustering





[Member 4 Name]



Built Nebula Pulse Theme, implemented XGBoost, and coordinated deployment



Nebula Pulse



XGBoost

Note: Replace [Member Name] with actual team member names.

📸 Screenshots







Welcome Page



Dashboard



Analysis















Note: Add screenshots to the screenshots/ folder in the repository.

🚀 Getting Started

Prerequisites





Python 3.8+



Git



Streamlit Cloud account (for deployment)

Installation





Clone the repository:

git clone https://github.com/yourusername/nebula-finance-lab.git
cd nebula-finance-lab



Install dependencies:

pip install -r requirements.txt



Run the app locally:

streamlit run app.py

Requirements

See requirements.txt for dependencies:

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

📊 Usage





Launch the App:





Run locally or access the deployed version (see Deployment).



Load Data:





Yahoo Finance: Enter a ticker (e.g., AAPL) and select a period (e.g., 1y).



File Upload: Upload a CSV/Excel file with columns (Date, Open, High, Low, Close, Volume).



Explore Themes:





Switch between Zombie, Futuristic, Game of Thrones, and Nebula Pulse themes.



Analyze Data:





View data in the Dashboard tab (charts, statistics).



Train ML models in the Analysis tab and download results.



Troubleshooting:





Clear cache if data fetching fails.



Use longer periods (1y, max) for better Yahoo Finance results.

🌐 Deployment

The app is deployed on Streamlit Cloud:
🔗 Nebula Finance Lab
Note: Replace with your actual Streamlit Cloud URL after deployment.

To deploy:





Push code to GitHub.



Connect to Streamlit Cloud, select the repository, and set app.py as the main file.



Ensure requirements.txt is included.

📢 LinkedIn Posts

Each team member has shared a demo on LinkedIn:





[Member 1 Name]: [Link to Post]



[Member 2 Name]: [Link to Post]



[Member 3 Name]: [Link to Post]



[Member 4 Name]: [Link to Post]

Note: Add actual LinkedIn post links after posting.

📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments





Instructor: Dr. Usama Arshad for guidance.



Libraries: Streamlit, yfinance, scikit-learn, Plotly, Matplotlib, and others.



Team: For collaborative efforts in building a creative financial ML app.



Nebula Finance Lab © 2025 | Developed for AF3005 Group Project
