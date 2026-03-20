Titanic Survival Analysis (EDA)
Project Overview

This project performs an Explatory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival.

The analysis focuses on how survival probability is affected by:

Passenger class

Gender

Age

Deck location

The goal is to extract meaningful insights from the data and identify key variables that would be useful in building a predictive model.

 Objectives

Explore and understand the dataset structure

Clean and prepare the data for analysis

Analyze survival patterns across different features

Identify the strongest factors influencing survival

Generate insights for future predictive modeling

 Dataset Summary

Rows: 891 passengers

Columns: 16 features

Each row represents an individual passenger

Key Features:

survived – Survival outcome

pclass – Passenger class

sex – Gender

age – Age

fare – Ticket fare

deck – Deck location

embarked / embark_town – Boarding location

alone – Whether passenger traveled alone

Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

🧹 Data Cleaning

The dataset contained missing values and inconsistent data types.

Cleaning steps:

Converted:

survived → boolean

alive → boolean

alone → Yes/No labels

Handled missing values:

age → filled with mode

deck → filled with "Unknown"

embarked & embark_town → filled with "Unknown"

Verified:

No duplicate records

Exploratory Data Analysis
Univariate & Categorical Analysis
Survival by Gender

Survival by Passenger ClaSS

Age Distribution

Survival by Deck

🔗 Bivariate Analysis
Correlation Heatmap

Passenger Class vs Survival (Boxplot)

💡 Key Insights
1. Gender was the strongest survival factor

Females had significantly higher survival rates

Males made up the majority of fatalities

2. Socioeconomic status mattered

First-class passengers had the highest survival rates

Third-class passengers were the most vulnerable

3. Age influenced survival

Young children had a survival advantage

Adults (especially 20–40) had the highest death rates

4. Deck location affected outcomes

Higher decks had better access to lifeboats

Lower decks were a disadvantage

📈 Conclusion

Survival on the Titanic was not random. It was heavily influenced by:

Gender

Passenger class

Age

Physical location on the ship

These factors reflect both social hierarchy and evacuation dynamics during the disaster.
