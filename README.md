# Employee-Attrition-Workforce-Analytics
# Employee Attrition & Workplace Analytics using Python

## 📌 Project Overview

This project analyzes employee attrition and workplace-related factors using Python. The objective is to understand patterns associated with employees leaving or staying in an organization and identify areas where employee retention strategies may be improved.

The project uses data cleaning, exploratory data analysis (EDA), statistical summaries, data visualization, correlation analysis, and outlier detection to investigate the relationship between attrition and different employee characteristics.

## 🎯 Project Objectives

- Calculate the overall employee attrition rate.
- Identify departments and job roles with higher attrition rates.
- Analyze the relationship between overtime and employee attrition.
- Compare monthly income between employees who left and those who stayed.
- Examine job satisfaction, work-life balance, and environment satisfaction.
- Investigate attrition patterns across age groups.
- Analyze the relationship between distance from home and attrition.
- Compare employee characteristics based on attrition status.
- Explore relationships between numerical variables using a correlation heatmap.
- Detect potential outliers using the Interquartile Range (IQR) method.
- Generate automatic business insights and suggested actions.

## 📂 Dataset

**Dataset file:** `Employee Attrition & Workplace Analytics.csv`

The dataset contains employee-related information, including:

- **Demographic information:** Age, Gender, and Marital Status
- **Employment information:** Department, Job Role, Job Level, and Business Travel
- **Compensation information:** Monthly Income and Percent Salary Hike
- **Employee satisfaction:** Job Satisfaction, Environment Satisfaction, and Work-Life Balance
- **Work experience:** Total Working Years, Years at Company, and Years With Current Manager
- **Work-related factors:** OverTime, Job Involvement, and Performance Rating
- **Target variable:** Attrition, indicating whether an employee left the organization

## 🛠️ Tools and Technologies

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab / Jupyter Notebook** – Development environment

## 🧹 Data Cleaning and Preparation

The project performs the following data preparation steps:

1. Loads the dataset using Pandas.
2. Checks the dataset's dimensions, column names, data types, and information.
3. Identifies missing values in each column and calculates the total number of missing values.
4. Checks for duplicate rows and removes exact duplicates.
5. Standardizes the `Attrition` column by removing extra whitespace and normalizing text capitalization.
6. Retains records with valid `Attrition` values of `Yes` or `No`.
7. Separates categorical and numerical columns.
8. Generates descriptive statistics for numerical and categorical variables.

## 📊 Analysis Performed

### 1. Overall Attrition Rate
- Calculates the number of employees who left and stayed.
- Computes the overall attrition percentage.
- Visualizes employee attrition using a count plot.

### 2. Attrition by Department
- Calculates the attrition rate for each department.
- Ranks departments according to their attrition rates.
- Displays the results using a bar chart.

### 3. Overtime and Attrition
- Compares attrition rates between employees who work overtime and those who do not.
- Uses a bar chart to visualize the results.

### 4. Monthly Income Analysis
- Compares employee counts, average income, and median income by attrition status.
- Uses box plots to examine income distributions among employees who left and stayed.

### 5. Job Satisfaction Analysis
- Calculates mean and median job satisfaction for each attrition group.
- Visualizes job satisfaction using a box plot.

### 6. Distance from Home Analysis
- Compares the average and median distance from home for employees who left and stayed.
- Uses a box plot to explore possible differences.

### 7. Attrition by Job Role
- Calculates attrition rates for different job roles.
- Identifies roles with comparatively higher attrition.
- Presents the results in a horizontal bar chart.

### 8. Age and Attrition
- Compares average and median age by attrition status.
- Groups employees into age ranges: 18–25, 26–35, 36–45, 46–55, and 56–65.
- Calculates and visualizes attrition rates for each age group.

### 9. Work-Life Balance
- Compares mean and median work-life balance scores for employees who left and stayed.
- Uses a box plot to examine differences in work-life balance.

### 10. Employee Comparison Analysis
Compares the average values of selected variables across attrition groups, including:

- Age
- Monthly Income
- Distance From Home
- Job Satisfaction
- Environment Satisfaction
- Work-Life Balance
- Years at Company
- Years With Current Manager
- Total Working Years
- Job Involvement

The project also examines attrition rates by Business Travel, Marital Status, Gender, and Education Field.

### 11. Correlation Heatmap
- Calculates correlations among selected numerical variables.
- Includes employee age, income, satisfaction scores, work experience, job level, salary hike, and performance rating.
- Uses a heatmap to visualize the strength and direction of relationships between variables.

### 12. Outlier Analysis
- Applies the Interquartile Range (IQR) method to identify potential outliers.
- Examines Age, Monthly Income, Distance From Home, and Years at Company.
- Calculates lower and upper outlier boundaries and the number of potential outliers.
- Uses box plots to visualize the distributions.

### 13. Automatic Business Insights
The code automatically summarizes:
- Overall attrition rate.
- Department with the highest attrition rate.
- Job role with the highest attrition rate.
- Attrition rates for employees who work overtime and those who do not.
- Average age, monthly income, distance from home, job satisfaction, and work-life balance by attrition status.

It also suggests business actions related to workload, employee retention, compensation, career development, satisfaction, and work-life balance.

## 💡 Business Insights and Recommendations

The analysis can help organizations:

- **Improve employee retention:** Investigate departments and job roles with higher attrition rates.
- **Review overtime policies:** Examine workload distribution and staffing levels where overtime is associated with higher attrition.
- **Support employee satisfaction:** Use employee feedback to identify opportunities to improve job and workplace satisfaction.
- **Review compensation and career development:** Explore whether income, growth opportunities, or career progression are associated with employee attrition.
- **Promote work-life balance:** Evaluate workplace practices that may support employee well-being and retention.
- **Monitor workforce trends:** Track attrition rates and relevant employee indicators over time.

*Note: Actual conclusions should be based on the numerical results and charts produced when the notebook is executed. Observed relationships indicate associations and do not, by themselves, prove causation.*

## 📈 Expected Project Outcomes

After running the notebook, the analysis produces:

- Employee attrition counts and overall attrition percentage.
- Attrition-rate tables for departments, job roles, overtime, age groups, and other categorical factors.
- Comparative statistics for employees who left and stayed.
- Charts and box plots for exploratory analysis.
- A correlation heatmap of selected numerical variables.
- An outlier summary table based on the IQR method.
- An automatically generated summary of business insights and suggested actions.

## 🚀 How to Run the Project

1. Download or clone this GitHub repository.
2. Download the dataset `Employee Attrition & Workplace Analytics.csv`.
3. Place the CSV file in the same directory as the notebook, or update the file path in the code.
4. Open `Employee Attrition & Workplace Analytics.ipynb` in Google Colab or Jupyter Notebook.
5. Install the required libraries if they are not already available:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

6. Run the notebook cells in order.
7. Review the generated tables, charts, and business insights.

## ⚠️ Limitations

- The analysis identifies patterns and associations, not definitive causes of employee attrition.
- Results depend on the quality, completeness, and representativeness of the dataset.
- Correlation does not necessarily imply causation.
- The notebook analyzes the available dataset and does not establish whether the observed patterns apply to every organization.

## 🏁 Conclusion

The **Employee Attrition & Workplace Analytics** project demonstrates how Python can be used to analyze workforce data and explore factors associated with employee retention. By combining data cleaning, descriptive statistics, visualization, correlation analysis, and outlier detection, the project provides a structured approach to understanding employee attrition and supporting data-informed HR decisions.

