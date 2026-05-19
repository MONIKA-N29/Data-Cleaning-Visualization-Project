 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

📌 Project Overview

This project focuses on cleaning, preprocessing, and analyzing the Titanic dataset to uncover meaningful insights about passenger survival patterns. The analysis includes handling missing values, removing duplicates, performing exploratory data analysis (EDA), and generating visualizations using Python libraries.

Developed as part of a Data Science Internship project.


📊 Dataset Information
Dataset:Titanic Dataset
Source: Kaggle Titanic Competition
File Used: `train.csv`

The dataset contains passenger details such as:
- Passenger ID
- Age
- Gender
- Passenger Class
- Fare
- Embarkation Point
- Survival Status


🎯 Objectives

- Clean and preprocess raw data
- Handle missing values and duplicates
- Perform exploratory data analysis
- Visualize important patterns and trends
- Extract meaningful business insights


 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation & Cleaning |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Google Colab | Development Environment |

🧹 Data Cleaning Process

The following preprocessing techniques were applied:

- Filled missing values in the `Age` column using median values
- Filled missing values in the `Embarked` column using mode
- Removed duplicate records
- Dropped the `Cabin` column due to excessive missing values
- Verified dataset consistency after cleaning


📈 Exploratory Data Analysis

The following analyses and visualizations were performed:

✔ Survival Analysis
- Survival count distribution
- Survival comparison by gender
- Survival comparison by passenger class

✔ Distribution Analysis
- Passenger age distribution
- Fare distribution

 ✔ Correlation Analysis
- Heatmap showing relationships between numerical features


📷 Visualizations

The project includes:
- Count plots
- Histograms
- Correlation heatmaps
- Comparative survival analysis charts

💡 Key Insights

- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers had a greater probability of survival.
- Most passengers belonged to the age group of 20–40 years.
- Passenger class and gender strongly influenced survival outcomes.

📌 Project Outcome

This project demonstrates practical skills in:
- Data preprocessing
- Exploratory data analysis
- Data visualization
- Insight extraction
- Python-based analytical workflows


🔮 Future Enhancements

- Build machine learning models for survival prediction
- Create interactive dashboards using Plotly or Power BI
- Deploy analysis using Streamlit

