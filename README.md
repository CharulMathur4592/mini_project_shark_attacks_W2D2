# 🦈 Shark Attacks Data Analysis

## 📌 Project Overview
The goal of this project is to clean and analyze a real-world dataset containing historical shark attack records in order to extract meaningful insights and identify patterns.

The dataset comes from the Global Shark Attack File (GSAF) and contains information about shark attacks including the date, location, activity, victim demographics, and shark species.

Because the dataset is messy and inconsistent, the main focus of this project is data cleaning, preprocessing, and exploratory data analysis (EDA).

## 🎯 Project Objectives

The main objectives of this project are:

1. Clean and preprocess a messy dataset
2. Handle missing and inconsistent data
3. Standardize variables and formats
4. Perform exploratory data analysis (EDA)
5. Identify trends and patterns in shark attacks
6. Communicate findings through visualizations

## 📂 Dataset Description
The dataset contains historical shark attack incidents worldwide. 

Key variables include:

1. **Date:** Date of the attack
2. **Year:** Year of the incident
3. **Type:** Type of attack (provoked/unprovoked)
4. **Country:** Country where the attack occurred
5. **Area:** Specific region
6. **Location:** Exact location
7. **Activity:** Activity performed during attack
8. **Sex:** Victim gender
9. **Age:** Victim age
10. **Injury:** Description of injuries
11. **Fatal (Y/N):** Whether the attack was fatal
12. **Species:** Shark species involved

The dataset required extensive cleaning due to:
1. Missing values
2. Inconsistent formatting
3. Mixed data types
4. Duplicate columns
5. Unstructured text entries

## 🧹 Data Cleaning Process

Several preprocessing steps were performed to prepare the data for analysis.

**1. Column Standardization:**
- Converted column names to lowercase
- Removed extra spaces
- Renamed inconsistent columns

**2. Removing Unnecessary Columns:**

Columns containing mostly missing values or irrelevant information were removed.

**3. Handling Missing Values:**
- Replaced placeholders such as "?", "unknown", or empty values with NaN
- Removed rows with insufficient information when necessary

**4. Cleaning the Age Column:**

The Age column contained inconsistent formats such as:
- "50+"
- "20s"
- "?"
- "teen"
- "30 or 32"

**Cleaning steps:**
- Extracted numeric values from text
- Converted to numeric format
- Replaced invalid values with NaN
- Created a cleaned column: Age_cleaned

**5. Data Type Conversion:**

Converted columns to appropriate data types:
- Year → numeric
- Age → numeric
- Fatal → categorical

## 📊 Exploratory Data Analysis
After cleaning the dataset, several analyses were performed.

**1. Shark Attacks Over Time:**

Examined how the number of attacks has changed across years.

**2. Attacks by Country:**

Identified countries with the highest number of recorded shark attacks.

**3. Activities During Attacks:**

Analyzed which activities are most associated with shark attacks, such as:
- Surfing
- Swimming
- Fishing
- Diving

**4. Fatal vs Non-Fatal Attacks:**

Compared the proportion of fatal and non-fatal incidents.

**5. Age Distribution:**

Explored the distribution of victim ages using the cleaned age data.

## 📈 Visualizations

Visualizations were created using:
- Matplotlib
- Seaborn
- Pandas

Examples include:
- Shark attacks by year
- Top countries with shark attacks
- Activity distribution
- Fatal vs non-fatal incidents
- Age distribution histogram

## 🛠 Tools & Libraries

The following tools were used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 👤 Authors
1. Charul Mathur
2. Charles Mensah
3. Helena Sospedra
4. Isailton Soares
5. Sulaiman Castineira Diaz