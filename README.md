Data Science Capstone Project
Life Expectancy Prediction Using Socioeconomic Indicators (2005–2015)

This repository contains the full submission for the HarvardX: Data Science Capstone Project, including:

📄 Report (PDF) – Final written analysis

📘 R Markdown Report (Rmd) – Source code used to generate the PDF

📜 R Script – Supervised machine learning workflow

📊 Dataset (CSV) – World life expectancy and socioeconomic indicators

📁 Project Structure

├── happines_raport.Rmd         # R Markdown report (main analysis)
├── happines_raport.pdf         # Final report in PDF format
├── word_happines.R             # R script performing ML tasks (GLM, RMSE, plots)
├── Data.csv                    # Dataset used for the analysis
├── Series - Metadata.csv       # Additional metadata provided with the dataset
└── README.md                   # Project documentation

🧠 Project Summary

This project analyzes global life expectancy between 2005–2015 using machine learning and statistical modeling.
We evaluate three predictive models:

Baseline Summation Model
A simple linear weighted sum of socioeconomic indicators.

GLM Model (2015 Only)
Supervised machine learning using a Generalized Linear Model on 2015 country data.

Full Panel GLM (2005–2015)
A longitudinal GLM including a Time variable to capture global life expectancy trends.

🔍 Key Methods

Data cleaning & preprocessing

Train/test split (70/30)

GLM supervised learning

RMSE evaluation

Visualization (Predicted vs Actual)

📈 Main Findings

The Full Panel GLM achieves the lowest RMSE, showing that multi-year data improves predictive power.

Child mortality, GDP, and secondary school enrollment are the strongest predictors of life expectancy.

Time has a positive effect, reflecting global health improvements over the decade.

⚙️ How to Reproduce

Clone the repository:

git clone https://github.com/hamzamann9962/harvard_DS-capstone-project.git


Open the project in RStudio:

Install required packages listed in the Rmd

Run the .R script or knit the .Rmd file

The PDF report will be generated automatically

📬 Author

Hamza Mannai
Industrial Computer Science & Automation
AI – Robotics – Cybersecurity
🌐 Portfolio: https://hamzamannai.com
