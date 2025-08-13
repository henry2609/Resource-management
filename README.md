Industrial Human Resource Geo-Visualization
📌 Project Overview
This project analyzes the industrial classification of the workforce in India to understand the distribution of main and marginal workers across industries, geographies, and demographics.
It updates outdated workforce data by applying EDA, feature engineering, NLP-based industry grouping, and visualization to provide policy-relevant insights.

The final deliverable includes:

A Streamlit + Plotly dashboard for interactive workforce exploration

A machine learning pipeline for classification & clustering

A PowerPoint presentation summarizing the problem, approach, tools, and key insights

🎯 Problem Statement
In India, industrial classification of the workforce is essential to understand labor distribution across various sectors.
Existing data is outdated, which affects policy-making and employment planning.
The goal is to update and visualize this classification by:

Worker type (main/marginal)

Gender

Section, division, and class

State and district geography

🛠 Tools & Technologies
Programming & Analysis:

Python, Pandas, NumPy

scikit-learn (ML modeling)

NLTK / spaCy (NLP industry grouping)

Visualization & Dashboard:

Plotly, Streamlit

Data Handling:

Excel/CSV, openpyxl

Development & Version Control:

Google Colab / VS Code

GitHub (public repo)

Presentation:

PowerPoint

🚀 Approach
Data Preparation

Merge multiple CSV files into a single DataFrame

Handle missing values, remove duplicates

Feature Engineering

Total worker counts (main + marginal)

Male/Female ratios

Rural/Urban workforce share

NLP-Based Industry Grouping

Map detailed industry descriptions to broad categories
(e.g., “Manufacturing plastic products” → “Manufacturing”)

Model Building

Classification: Predict industry category based on location & workforce data

Clustering: Group states/industries with similar workforce patterns

Visualization

Streamlit dashboard with:

KPI cards

Industry bar charts

Treemaps & Sunbursts

Gender & Rural/Urban splits

Auto-generated insights

📊 EDA Insights (Sample)
(Replace with your actual analysis results)

Largest Industry: Manufacturing plastics — 120,000 workers

Gender Ratio: Median M/F = 1.3 (male-dominated)

Rural Share: 62% median

Top States: Maharashtra, Tamil Nadu, Uttar Pradesh

Urban-heavy sectors: IT services, finance

Rural-heavy sectors: Agriculture-related manufacturing, poultry

📂 Project Structure
bash
Copy
Edit
├── app.py                         # Streamlit dashboard app
├── data_preprocessing.py          # Load & clean data
├── feature_engineering.py         # Feature creation & encoding
├── model_building.py              # Classification & regression models
├── clustering_analysis.py         # Clustering & segmentation
├── combined_final_cleaned.xlsx    # Dataset
├── Industrial_HR_GeoViz_Presentation.pptx  # Presentation
└── README.md                      # Project documentation
▶️ How to Run
Local
bash
Copy
Edit
pip install -r requirements.txt
streamlit run app.py
Google Colab
Upload your dataset to /content

Install dependencies:

python
Copy
Edit
!pip install streamlit pyngrok plotly pandas openpyxl
Run Streamlit in Colab using ngrok (see code in notebook)

📜 Deliverables
Streamlit Dashboard for workforce analysis

Machine Learning Models for classification/clustering

PowerPoint Presentation with:

Problem Statement

Tools Used

Approach

EDA Insights

