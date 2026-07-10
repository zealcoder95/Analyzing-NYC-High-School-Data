# Title: NYC High School Analysis

- **Category:** Data Analysis
- **Featured:** true
- **Tags:**
  - Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - EDA

This project analyzes the relationship between **SAT scores** in New York City high schools and various **socio-economic** and **real estate factors** across different boroughs. The goal is to uncover insights that can help educators, policymakers, and homebuyers make informed decisions.

## **Project Overview**

In this project, I explored how various factors such as school resources, safety perceptions, student demographics, and real estate prices affect academic performance (measured through SAT scores). By merging school performance data with NYC property sales data, I was able to analyze the interplay between education and real estate.

### **Key Insights:**

- **School Resources**: Schools with higher resource allocation and larger student populations tend to achieve higher SAT scores.
- **Safety Perceptions**: Both students’ and teachers’ perceptions of school safety are positively correlated with better academic outcomes.
- **Demographic Disparities**: Schools with higher percentages of White and Asian students generally show better SAT performance, while schools with a higher proportion of Black and Hispanic students tend to have lower scores, potentially due to systemic inequalities.
- **Property Prices and Education**: There is a notable correlation between higher property prices and better school performance in boroughs like Manhattan and Brooklyn. However, in boroughs like Queens and Staten Island, more cost-effective options with relatively good schools are available.

## **Data Sources**

- **NYC High School Data**: Information on student demographics, SAT scores, safety perceptions, and other factors related to school performance.
- **NYC Property Sales Data**: Data on real estate sales across the five boroughs of New York City.

## **Technologies Used**

- **Python**: For data manipulation and analysis.
- **Pandas**: To clean and transform the datasets.
- **Matplotlib & Seaborn**: For data visualization and generating insightful plots.
- **NumPy**: For numerical operations and calculations.
- **Jupyter Notebook**: To document and run the analysis.

## **Project Structure**

- **data/**: Contains the datasets used in the project.
  - `combined.csv`: School performance data.
  - `nyc-rolling-sales.csv`: Property sales data for NYC.
- **notebooks/**: Contains the Jupyter Notebook with all analysis and visualizations.
  - `Analyzing_NYC_High_School_Data.ipynb`: The main notebook containing the analysis.
- **README.md**: Project documentation.

## **Key Analysis Steps**

1. **Data Cleaning and Preprocessing**: 
   - Missing data handling, data type conversions, and merging the datasets on the borough level.
   
2. **Exploratory Data Analysis (EDA)**: 
   - Investigated relationships between SAT scores and variables such as safety perceptions, demographic information, and property prices.
   
3. **Visualizations**: 
   - Generated scatter plots, bar charts, and correlation matrices to illustrate key findings.

4. **Conclusions**: 
   - Highlighted the link between education quality, safety perceptions, socio-economic factors, and property prices.

## **Usage**

To run the analysis:

1. Clone this repository:
   ```bash
   git clone https://github.com/zealcoder95/Analyzing-NYC-High-School-Data.git
   ```
2. Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to reproduce the analysis.

## **Results and Insights**

This analysis provides valuable insights for:
- **Homebuyers** looking for a balance between property prices and school quality.
- **Policymakers** focusing on improving educational outcomes through resource allocation.
- **Educators** interested in the impact of socio-economic factors on student performance.

## **Project Links**

- **Kaggle Project**: [Analyzing NYC High School Data](https://www.kaggle.com/code/gizemglc/analyzing-nyc-high-school-data)

## **Contributions**

Feel free to fork this repository and submit pull requests for improvements or additional features!
