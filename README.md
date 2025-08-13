Industrial Human Resource Geo-Visualization
📌 Project Overview
Analyze the industrial classification of India’s workforce to understand worker distribution by sector, geography, and demographics.

Update outdated workforce data using EDA, ML, and NLP for more accurate policy-making insights.

Build an interactive Streamlit + Plotly dashboard for data exploration.

Deliver a PowerPoint presentation summarizing the project’s problem, tools, approach, and findings.

🎯 Problem Statement
Industrial classification data in India is outdated.

Workers are categorized as main or marginal, excluding cultivators/agricultural laborers.

Current workforce breakdown by gender, division, and geography is incomplete.

Objective: Provide updated, accurate workforce classification for decision-making.

🛠 Tools & Technologies
Languages & Libraries:

Python, Pandas, NumPy

scikit-learn (ML)

NLTK / spaCy (NLP)

Visualization:

Plotly

Streamlit

Data Handling:

Excel / CSV

openpyxl

Development:

Google Colab / VS Code

GitHub (Public Repo)

Presentation:

Microsoft PowerPoint

🚀 Approach
Data Preparation

Merge multiple CSV files into a unified DataFrame.

Handle missing values & duplicates.

Feature Engineering

Compute total workers (main + marginal).

Calculate male/female ratios.

Determine rural/urban worker shares.

NLP Industry Grouping

Map specific industry names to broader categories.

Model Building

Classification: Predict industry category.

Clustering: Group similar states/industries.

Visualization

Build an interactive dashboard with KPIs, charts, and insights.

📊 EDA Insights (Sample)
Top Industry: Manufacturing plastics — 120,000 workers.

Gender Ratio: Median M/F ratio = 1.3 → male-dominated.

Rural Workforce Share: 62% median across industries.

Top States: Maharashtra, Tamil Nadu, Uttar Pradesh.

Urban-heavy Sectors: IT services, finance.

Rural-heavy Sectors: Agriculture-related manufacturing, poultry.

📂 Project Structure
bash

├── app.py                         # Streamlit dashboard app
├── data_preprocessing.py          # Load & clean data
├── feature_engineering.py         # Feature creation & encoding
├── model_building.py              # Classification & regression models
├── clustering_analysis.py         # Clustering & segmentation
├── combined_final_cleaned.xlsx    # Dataset
├── Industrial_HR_GeoViz_Presentation.pptx  # Presentation
└── README.md                      # Project documentation
▶️ How to Run
Local:

bash

pip install -r requirements.txt
streamlit run app.py
Google Colab:

Upload dataset to /content

Install:

python

!pip install streamlit pyngrok plotly pandas openpyxl
Run Streamlit via ngrok.

📜 Deliverables
Streamlit Dashboard for workforce analysis

Machine Learning Models for classification/clustering

PowerPoint Presentation covering:

Problem Statement

Tools Used

Approach

EDA Insights
