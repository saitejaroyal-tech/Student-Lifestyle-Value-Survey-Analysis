🎓 Student Lifestyle & Value Survey Analysis

An end-to-end exploratory data analysis project analyzing how lifestyle habits, social factors, and support systems influence student well being.

## Overview
This project explores how **student lifestyle factors** influence **mental stress levels and academic performance**.
The analysis uses **Python-based exploratory data analysis (EDA)** to identify patterns between daily habits and student well-being.

Factors studied include:

* Study hours
* Sleep duration
* Social media usage
* Family support
* Financial stress
* Academic performance (GPA)

---

## Data Processing

The dataset was cleaned and prepared before analysis.

Steps performed:

* Removed missing values and duplicates
* Standardized column names
* Scaled selected numerical variables for easier comparison
  
## Feature Engineering
New categorical columns were created to make analysis easier and visualizations clearer.
Examples:
* **Stress Category** – Low, Moderate, High
* **Sleep Category** – Low Sleep, Moderate Sleep, High Sleep
* **Study Category** – Low, Moderate, High Study Hours
* **Social Media Usage Category** – Low, Moderate, Heavy
* **Family Support Category** – Low, Moderate, High
* **Financial Stress Category** – Low, Moderate, High

These categories help analyze behavioral patterns among students.

## Exploratory Data Analysis

Different visualizations were used to understand relationships between variables:

* **Pie Charts** – Distribution of lifestyle categories
* **Box Plots** – Comparison of stress levels across lifestyle factors
* **Statistical summaries** – Mean, median, quartiles, and variatio
## Tools Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Plotly
## Project Structure
student-lifestyle-analysis
│
├── analysis.ipynb
├── dataset.csv
└── README.MD

🧠 Key Insights
1.Balanced sleep and moderate study hours reduce mental stress more effectively than extreme effort
2.Financial stress significantly impacts mental well-being, even when GPA remains stable
Strong family support correlates with healthier coping mechanisms and lower stress
3.Many highly stressed students do not seek counseling, indicating an awareness or stigma gap
4.Healthy lifestyle habits (exercise and diet) act as protective factors against stress
At-risk student groups can be identified using combined lifestyle and stress indicators
