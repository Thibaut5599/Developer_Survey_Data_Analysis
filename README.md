# Developer Survey Data Analysis

This project was followed as part of the Coursera training [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst?) during the ninth course entitled "IBM Data Analyst Capstone Project". This is a guided project.
This project was designed by Mr. Ramesh Sannareddy (Data Enginnering Subject Matter Expert at IBM) and Mr. Rav Ahuja (CCO & Global Program Director at IBM).

## Project Overview
This project focuses on analyzing a dataset from a developer survey to identify key trends in programming languages, database skills, and respondent demographics. The dataset includes responses from participants to various survey questions.

## Objectives
- What are the top programming languages in demand ?
- What are the top database skills in demand ?
- Who are the respondents to the survey?
  - Gender
  - Country
  - Age
  - Education level

## Project Contents 
- **Datasets_Database folder**
  - **Datasets :** m2_survey_data.zip is the compressed folder containing m2_survey_data.csv, used to create the database (SQLite file, cf. below) ; m5_survey_data_demographics.csv & m5_survey_data_technologies_normalised.csv are used for dashboard and report.
  - **Database :** SQLite file (m4_survey_data.zip is the compressed folder containing m4_survey_data.sqlite). It's a SQLite database with 24 tables; 23 tables correspond to survey questions and contain response counts, while the "master" table includes the remaining data columns.
- **Jupyter Notebook :** Developer_Survey_Data_Analysis.ipynb file shows data exploration using m4_survey_data.sqlite database.
- **Screenshots :** Screenshots_Plotly_Charts folder contains some PNG files corresponding to the plotly graphics screenshots inserted in the Jupyter Notebook.
- **IMB Cognos Analytics Dashboard :** Dashboard_CognosAnalytics.pdf file is a dashboard (in pdf format) allowing anyone to answer the questions asked in the "Objectives" section using the different visualizations.
- **Report :** Report_PowerPoint.pdf is a PowerPoint report (in pdf format) which presents, among other things, the various results and their implications as well as a conclusion.

## Results and Conclusion
**Programming Language Trend**
- **JavaScript and HTML/CSS** are the most popular and in-demand languages, indicating their essential role in maintaining job market relevance.
- **SQL** is widely used but shows less interest for further learning, possibly due to developer familiarity or the rise of NoSQL alternatives.
- **Go** shows high learning demand, likely for its performance and use in backend development.

**Databases Trends**
- **PostgreSQL** is both widely used and in demand, valued for its flexibility and standards compliance.
- **MongoDB** ranks high in desired skills, reflecting a growing interest in NoSQL.
- **MySQL** retains strong industry usage and interest, affirming its robustness

**Overall Findings and Implications**
- **SQL** is fundamental, but **NoSQL** is increasingly popular, necessitating skills in both
- **JavaScript** and **HTML/CSS** remain key, with a need for ongoing learning investments.
- Respondents are predominantly young, educated men, highlighting diversity improvement opportunities in tech.

**Conclusion**

This study indicates that classic web technologies are still vital, yet there's a growing interest in modern languages like Go. Traditional relational databases remain fundamental, while newer, flexible options like MongoDB are gaining traction. Additionally, the data reflect a tech industry dominated by young, highly educated men, pointing to opportunities for gender diversity and ongoing skill development.

## Usage
1. **Clone the repository** (enter the following command in a terminal) :

   git clone https://github.com/Thibaut5599/Developer_Survey_Data_Analysis.git
   
2. **Open the Jupyter Notebook :** Once you have cloned the repository, open Developer_Survey_Data_Analysis.ipynb file using Jupyter Notebook or JupyterLab (enter the following command in a terminal) :
   
   jupyter notebook Developer_Survey_Data_Analysis.ipynb

## Authors
Project designed by Ramesh Sannareddy and Rav Ahuja (IBM), carried out by Thibaut LANNERS.
