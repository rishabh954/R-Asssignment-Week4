# introduction

Weather plays a crucial role in our daily lives and influences various aspects such as agriculture, transportation, and lifestyle.
In this project, we analyze weather data (temperature, humidity, and rainfall) for multiple cities. The goal is to clean and transform the dataset, calculate weekly averages, identify weather patterns, and visualize the results for meaningful insights.

By performing this analysis in R, we strengthen our skills in data manipulation, summarization, and visualization using powerful libraries like dplyr, ggplot2, and lubridate.

# Objectives

1. Perform data inspection and handle missing values.

2. Clean and transform the dataset (e.g., convert temperature to Fahrenheit).

3. Calculate weekly averages for temperature, humidity, and rainfall.

4. Compare weather patterns across cities.

5. Visualize results using ggplot2 (line plots, bar plots, boxplots).

# Dataset

Synthetic dataset created for 7 cities: Delhi, Mumbai, Chennai, Kolkata, Bangalore, Hyderabad, Ahmedabad.

Contains 45 days of daily data with some missing values (NA).

Columns:

* Date

* City

* Temperature (°C)

* Humidity (%)

* Rainfall (mm)

# Tools & Libraries

* R

* Libraries: dplyr, ggplot2, lubridate

# Key Analyses

* Identify the hottest and coldest cities.

* Find the day with highest rainfall per city.

* Compare average humidity levels between cities.

* Show temperature trends over time (line graph).

* Weekly rainfall comparison (bar chart).

* Humidity distribution across cities (boxplot).

# How to Run

1. Clone the repository:

 * git clone https://github.com/rishabh954/R-Asssignment-Week4.git 
  
 * cd weather-analysis-r


2. Open weather.Rmd in RStudio.

3. Run all code chunks or knit the document to HTML/PDF.

# Outputs

1. Plot line graphs to show temperature trends of all cities over time.
   
   <img width="1281" height="682" alt="Screenshot 2025-09-13 153905" src="https://github.com/user-attachments/assets/108aae1a-334c-491c-b5ec-f01b23ce18f1" />

2. Create bar plots for weekly average rainfall comparison

  <img width="1207" height="688" alt="Screenshot 2025-09-13 154058" src="https://github.com/user-attachments/assets/cdd2d274-4c2d-42b8-89f7-b4f1537b5ef8" />

3. Use boxplots to show humidity distribution across cities.

  <img width="1174" height="683" alt="Screenshot 2025-09-13 154227" src="https://github.com/user-attachments/assets/74e41cf5-4b12-49d4-b8b6-caa554107c24" />

# Conclusion

* The analysis revealed interesting weather patterns across different cities:

* The hottest and coldest cities were identified based on average temperatures.

* The day with the highest rainfall for each city was highlighted.

* Humidity levels showed notable differences between cities.

Weekly averages helped smooth short-term fluctuations and gave a clearer view of long-term trends.

Through visualization, it became easier to compare trends and distributions across cities.
Overall, this project demonstrates the usefulness of R programming in handling real-world datasets, cleaning missing values, summarizing information, and creating clear visual stories from data.



