# Poverty-Analysis-in-the-US-using-R-and-Tableau
# Project Overview
This project involves exploratory data analysis (EDA) of poverty data across the United States. The goal is to identify patterns and correlations between poverty levels and educational attainment. Specifically, the analysis focuses on the relationship between the number of people living below the poverty line and the number of individuals without a high school diploma. Using R for statistical analysis and Tableau for visualization, the project provides insights into how these variables are distributed across states and counties and highlights regions most affected by poverty.

This analysis was conducted as part of a second-semester data mining course. While the project provides valuable initial insights, further in-depth analysis is required to explore additional factors influencing poverty and educational attainment.

# Case Description
Poverty continues to be a pressing issue in many parts of the world, including the United States. Understanding the factors that contribute to poverty can inform policymakers and organizations that aim to reduce poverty rates. This project is centered on analyzing U.S. poverty data at the state and county levels. The key focus is on two main variables:
- The number of people living below the poverty line.
- The number of individuals without a high school diploma.

Using these variables, the project seeks to explore the relationship between educational attainment and poverty. By identifying regions with high poverty rates and low educational attainment, the analysis aims to understand how lack of education might influence poverty levels, enabling more targeted interventions.

# Objectives
- Analyze poverty levels and educational attainment across U.S. states and counties to identify relationships between poverty rates and the number of individuals without a high school diploma.
- Assist policymakers and organizations by pinpointing regions with high poverty and low educational attainment, providing data-driven insights for targeted interventions.
- Build a correlation model to explore the impact of education (measured by high school diploma attainment) on poverty levels in different regions of the U.S.
- Provide interactive visualizations using Tableau to allow stakeholders to easily explore the data and gain insights into which regions are most affected by poverty and lack of education.

# Project Steps and Features
1. Data Import and Cleaning:
- The dataset contains 181 columns and 3,144 rows, with demographic, health, and educational information across U.S. counties.

- Key variables used include:
    - state: The U.S. state name.
    - county: The county name within the state.
    - num_below_poverty: The number of people living below the poverty line.
    - num_no_highschool_diploma: The number of individuals without a high school diploma.

- Initial data cleaning involved:
    - Removing irrelevant columns.
    - Identifying and handling missing values.
    - Verifying the accuracy of the data.

2. Exploratory Data Analysis:
- Conducted an initial assessment of the dataset to understand the distribution of poverty and education-related data.
- Identified top 10 states and counties with the highest poverty rates.
- Visualized these patterns using bar plots and summaries to identify where poverty and lack of education are most prevalent.

3. Correlation Analysis:
- A Pearson correlation test was conducted between the number of people living below the poverty line and the number of individuals without a high school diploma.
- The correlation was found to be close to 1, suggesting a strong positive relationship, i.e., as the poverty rate increases, so does the number of individuals without a high school diploma.

4. Data Visualization with Tableau:
- Created interactive maps and charts to visualize the geographical distribution of poverty and educational attainment:
  - State-level Poverty Map: Displayed using a choropleth map to show the variation in poverty levels across U.S. states.
  - County-level Poverty Map: Highlighted the counties with the highest poverty levels, specifically showing Los Angeles County as the most affected.
  - Poverty and Education Statistics Barplot: Illustrated the relationship between poverty rates and the number of people without high school diplomas across different counties.

5. Dashboard Creation:
- An interactive Tableau dashboard was developed to present all the visual insights in one place. The dashboard allows users to explore data in a user-friendly manner, facilitating better understanding of how poverty and education vary across the country.

# Tools and Technologies Used
- Language: R Programming
- Libraries: ggplot2, dplyr, corrplot and others.
- Dashboard: Tableau

# Challenges
- Handling Large Datasets: The dataset consisted of numerous columns (181 in total), and determining which columns were relevant for analysis required careful data inspection and domain knowledge.
- Dealing with Missing Values: Ensuring that missing data didn't bias the analysis was a key challenge. Thorough checks for missing values were conducted, and appropriate actions (such as imputing or removing) were taken.
- Correlation Complexity: Calculating and interpreting the correlation between educational attainment and poverty, while accounting for regional variations, required rigorous statistical analysis.
- Visualizing Large-Scale Data: Creating a clear and informative visualization from such a large dataset, especially when dealing with geographical maps, posed some performance challenges in Tableau.

# Conclusion
This project provides valuable insights into the relationship between poverty and educational attainment in the United States. The analysis demonstrated a strong positive correlation between poverty rates and the number of individuals without a high school diploma, indicating that education plays a crucial role in addressing poverty.

The interactive visualizations developed in Tableau allow policymakers and stakeholders to explore these insights further and target regions with high poverty and low educational attainment. These findings underscore the importance of educational programs as part of efforts to reduce poverty, particularly in regions like California and Los Angeles County, which were identified as having the highest poverty rates.
