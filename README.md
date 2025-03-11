# Exploratory Data Analysis of Student Performance Data

**Project Description:**

This project explores a dataset related to student performance and demographics, with a focus on identifying trends and patterns, particularly for at-risk student groups. The dataset contains information on student demographics, academic subjects, program types, outcomes, and performance indicators.

**Data Analysis:**

The analysis involved the following key steps:

1. **Data Cleaning:**
   * Handling missing values in columns like 'Characteristics', 'Academic Subject', 'Program Type', and 'Outcome' (over 80% missing).
   * Removing 975 identified duplicate rows.
   * Converting 'Value', 'Denominator', and 'Numerator' columns to numeric data types, coercing errors to NaN.
   * Imputing missing values in 'Denominator' and 'Numerator' with their respective medians.

2. **Exploratory Analysis:**
   * Analyzing the distributions of key numerical variables ('Value', 'Denominator', 'Numerator') using histograms and box plots.
   * Exploring the relationship between 'Value' and categorical variables like 'State' and 'Data Description' using group-wise summary statistics and box plots.
   * Identifying potential outliers in 'Value', 'Denominator', and 'Numerator' columns.

**Key Findings:**

* The dataset exhibits significant data quality issues, including a high percentage of missing data and duplicate rows.
* The 'Value' column, representing a key performance indicator, shows a wide range and potential outliers, warranting further investigation.
* Relationships between 'Value' and categorical variables like 'State' and 'Data Description' were observed and visualized.
* Further analysis is needed to explore the relationships between 'Value', 'Denominator', and 'Numerator' and to address the identified outliers.

**Usage:**

To replicate the analysis:

1. Download the dataset used in this project ('Data Download Tool.csv').
2. Open the provided Google Colab notebook.
3. Execute the code cells sequentially to reproduce the analysis steps and visualizations.

**Limitations:**

* The analysis is limited by the quality and completeness of the dataset.
* The imputation method used for missing values might introduce bias.
* Further investigation is needed to confirm the significance of observed trends and address outliers.

**Next Steps:**

* Address data quality issues by considering more advanced imputation techniques or removing incomplete records.
* Perform a deeper analysis of outliers in 'Value', 'Denominator', and 'Numerator' to determine their cause and potential impact.
* Explore the relationship between 'Value' and other categorical columns like 'Age/Grade' and potentially 'Subgroup Characteristics' if available.
* Conduct statistical testing to validate the observed trends and relationships.

**Contributing:**

Contributions and suggestions for further analysis are welcome. Please open an issue to discuss any proposed changes or additions.

**Contact:**

[Your Name/Username] - [Link to your GitHub Profile (Optional)]

**License:**

[Choose a license, e.g., MIT License]
