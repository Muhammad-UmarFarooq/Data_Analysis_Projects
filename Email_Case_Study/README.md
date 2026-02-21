📊 Exploratory Data Analysis (EDA) on Gmail Takeout Dataset

Academic Case Study

---

📌 Project Overview

This project is an academic case study conducted as part of my engineering coursework. The objective is to perform Exploratory Data Analysis (EDA) on personal Gmail data exported using Google Takeout, with the aim of understanding email communication patterns and gaining hands-on experience working with real-world unstructured data.

The project focuses on data extraction, cleaning, feature engineering, and visualization, rather than predictive modeling.

---

🎯 Objectives

- Import and process raw Gmail .mbox data

- Clean and transform email metadata such as:

Subject

Sender

Date

Labels

Threads

- Perform descriptive statistical analysis

- Engineer meaningful features, including:

Day of the week emails were sent/received

Time of day of emails

Year-wise communication trends

- Visualize communication patterns using charts and word clouds

---

🛠️ Tools & Libraries

- Python

- Pandas – Data manipulation and analysis

- Matplotlib & Seaborn – Data visualization

- WordCloud – Text analysis and visualization

- Mailbox, CSV – Email data extraction and transformation

---

📂 Dataset

- Data Source: Google Takeout (Gmail Export)

- Original Format: .mbox

- Processed Format: .csv

- Fields Extracted

subject

from

date

to (dropped during preprocessing)

label

thread

⚠️ Note:
The dataset contains personal email metadata only.
For privacy and ethical reasons, the dataset is not shared publicly.

---

🔑 Key Steps Performed
1️⃣ Data Loading

- Converted .mbox files into a structured .csv format

- Imported data into Pandas DataFrames

2️⃣ Data Cleaning

- Handled missing and inconsistent values

- Removed irrelevant or unused columns

- Standardized date and time formats

3️⃣ Feature Engineering

- Extracted:

Day of the week

Time of day

Year from email timestamps

4️⃣ Descriptive Analysis

- Analyzed email counts and distributions
 
- Compared sent vs. received emails

5️⃣ Data Visualization

- Bar charts for emails by day of the week

- Comparison plots for sent vs. received emails

- Scatter plots showing time-based patterns

- Word cloud visualization of email subjects

---

📊 Sample Visualizations

- Emails by Day of the Week

- Sent vs. Received Emails

- Scatter Plot (Time of Day vs Year)

- Word Cloud of Email Subjects

---

📈 Key Insights

- Clear differences observed between sent and received email activity

- Higher communication frequency on specific days of the week

- Word cloud revealed commonly used subject-line terms

- Strong time-based patterns visible across different years and times of day

---

📚 Learnings

- Working with unstructured real-world datasets

- Converting .mbox files into structured formats

- Importance of feature engineering in time-series analysis

- Using visualizations to communicate data-driven insights effectively

---

🔗 Project Links

📂 Full Project Code:
https://github.com/Muhammad-UmarFarooq/Projects

---

📄 LinkedIn Post:
https://www.linkedin.com/posts/muhammadumarfarooq584_datascience-eda-python-activity-7371908944979464192-Nx9f

---

❌ Machine Learning Scope

This project focuses exclusively on exploratory data analysis and visualization.
Machine learning models were not applied, as the goal was to analyze patterns and derive insights rather than prediction.

---

⭐ Acknowledgments

- Google Takeout for providing data export functionality

- Python open-source community
