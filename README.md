A Machine Learning Solution for Data-Driven Crime Analytics in South Africa
This repository contains a data science project that analyzes crime patterns in South Africa. It uses machine learning to predict crime hotspots and forecast future trends, presenting the results in an interactive web dashboard built with Streamlit.

📝 Project Overview
Crime remains one of South Africa's most significant challenges. This project leverages data analytics to provide law enforcement and policymakers with tools for a more proactive and data-informed approach to crime prevention. The solution is twofold:

A. Hotspot Classification: A classification model that predicts whether a police precinct will qualify as a high-crime hotspot based on socio-economic and demographic factors.

B. Trend Forecasting: A time-series model that forecasts future trends for specific crime categories, helping to anticipate seasonal spikes and emerging patterns.

The entire analysis, from data exploration to model prediction, is presented in a user-friendly Streamlit dashboard (app.py).

✨ Key Features
Interactive EDA: A dashboard with multiple visualizations (pie charts, bar charts, heatmaps) to explore the crime data.

Hotspot Prediction: A Random Forest model that identifies potential high-risk areas with clear performance metrics.

Crime Forecasting: A Prophet model to forecast future crime trends for any selected category.

Self-Contained Dashboard: A single Streamlit application to demonstrate all findings locally.

🛠️ Technology Stack
Language: Python

Data Manipulation: Pandas

Data Visualization: Matplotlib & Seaborn

Machine Learning: Scikit-learn (Random Forest), Prophet (Time-series Forecasting)

Web Dashboard: Streamlit

📂 Data Sources
This project utilizes two primary datasets available on Kaggle:

Crime Incidents: Crime Statistics for South Africa (2005-2015)

Socio-Economic Data: General Household Survey Data (2012-2022) - Note: A simplified population dataset (ProvincePopulation.csv) is used in the final Streamlit app for faster loading.

🚀 How to Run the Project Locally
Follow these steps to set up and run the dashboard on your machine.

1. Clone the Repository
Clone this repository to your local machine using git:

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
cd your-repository-name

2. Create a Virtual Environment (Recommended)
It's a good practice to create a virtual environment to manage project dependencies.

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
.\venv\Scripts\activate

3. Install Required Libraries
Install all the necessary libraries using the provided requirements.txt file.

pip install -r requirements.txt

Tip: To create the requirements.txt file yourself, run this command in your terminal: pip freeze > requirements.txt

4. Place Data Files in the Project Folder
Download the required CSV files (SouthAfricaCrimeStats_v2.csv and ProvincePopulation.csv) from the links above and place them in the root directory of the project folder. Your folder should look like this:

/your-repository-name
|-- app.py
|-- README.md
|-- requirements.txt
|-- SouthAfricaCrimeStats_v2.csv
|-- ProvincePopulation.csv

5. Run the Streamlit Application
You are now ready to launch the dashboard! Run the following command in your terminal:

streamlit run app.py

Your default web browser will automatically open a new tab with the running application.

This README will give anyone who visits your repository a clear and professional understanding of your work.
