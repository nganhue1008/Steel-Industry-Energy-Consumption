# Steel-Industry-Energy-Consumption

## Introduction & Business Statement 
- Addresses key learning outcomes by requiring proficiency in R for data processing and analysis, utilization of advanced regression methods to extract meaningful insights for real-world business problems. 
- Information gathered is from the DAEWOO Steel Co. Ltd in Gwangyang, South Korea
- Electricity consumption data stored in a cloud-based system, available on Korea Electric Power Corporation's website
- Project aims to understand energy dynamics and optimize operations
- Objective: unravel trends and factors influencing energy usage
- Aim: Provide actionable insights for optimizing energy utilization and enhancing efficiency

## Questions and Methods

Questions to be Answered:  
- Are there significant differences in energy usage, reactive power, or other metrics between weekdays and weekends within the steel industry?  
- What are the overall trends in energy usage over the observed period, and are there any identifiable patterns or anomalies?  
- Is there a significant association between load type and energy usage within the steel industry?  
- How can we handle multicollinearity and improve the accuracy of time series forecasts for energy usage using advanced regression techniques such as Lasso and Ridge regression?  
The chosen methods for analysis were selected based on their appropriateness in  addressing the specific research questions and leveraging the characteristics of the available data:  
- T-test or ANOVA: The dataset includes information on energy usage, reactive power, and other metrics, along with the corresponding days of the week (Weekdays vs. Weekends). 
By conducting a t-test or ANOVA, we can determine if there are statistically significant 
differences in these metrics based on the day of the week.
- Linear Regression: Linear regression allows us to model the relationship between independent variables (such as time) and a dependent variable (energy usage). By fitting a linear regression model with time as the independent variable, we can identify any overall 
trends in energy usage and quantify their significance.  
- Chi-Square Test: The dataset includes information on load type (a categorical variable) and energy usage. By conducting a chi-square test, we can determine if there is a significant association between load type and energy usage within the steel industry.  
- Lasso and Ridge Regression: By applying Lasso and Ridge regression, we can mitigate multicollinearity, improve the accuracy of time series forecasts for energy usage, and identify the most influential predictors in the dataset.

## Data description 
- Data (Continuous): time data taken on the first of the month 
- Usage_kWh (Continuous): Industry Energy Consumption kWh 
- Lagging (Continuous): Current reactive power kVarh 
- Leading Current reactive power (Continuous): kVarh 
- CO2(Continuous): ppm 
- NSM (Continuous): Number of Seconds from midnight S 
- Week status (Categorical): (Weekend (0) or a Weekday(1)) 
- Day of week (Categorical): Sunday, Monday : Saturday 
- Load Type (Categorical): Light Load, Medium Load, Maximum Load

## Business recommendation 
- Implement energy efficiency measures tailored to the specific load types and operational requirements
- Develop strategies for managing energy usage based on time-related factors such as weekdays vs. weekends and peak vs. off-peak hours.
- Establish a system for continuous monitoring and analysis of energy usage data to identify trends, anomalies, and opportunities for improvement.
- Provide training and raise awareness among employees about the importance of energy conservation and efficiency measures

