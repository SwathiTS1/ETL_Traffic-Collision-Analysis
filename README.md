# ETL_Traffic-Collision-Analysis
Analyzed large-scale traffic collision data using PySpark and AWS to clean, transform, and explore crash patterns. Generated insights to support traffic safety improvements and urban planning decisions.


**Problem Statement:**
Traffic collisions result in significant human and economic costs. Understanding collision trends, severity, environmental factors, and geographic hotspots is essential for improving road safety. This project aims to analyze large-scale collision datasets to identify accident-prone locations, dangerous time periods, and key contributing factors such as weather, lighting, and road surface conditions.

**Dataset :**
The dataset contains historical traffic collision records, including:
Collision severity
Weather conditions
Lighting conditions
Road surface conditions
Victim and injury counts
Geographic locations
Collision date and time
County and roadway information

The data was processed using PySpark on cloud infrastructure and analyzed without sampling to preserve complete collision information.

**Exploratory Data Analysis**

Data Preparation & Cleaning - 

Identified sparse columns and removed highly incomplete attributes.
Handled missing values using appropriate replacement strategies.
Converted data types for analytical processing.
Removed duplicate collision records.
Performed outlier detection using the IQR method.
Preserved valid extreme injury events and capped unrealistic distance outliers.

Key Visualizations - 

Collision severity distribution
Weather condition analysis
Victim age distribution
Collision severity vs victim counts
Weather vs collision severity heatmaps
Lighting condition analysis
Weekday collision trends
Geographic collision distribution
Monthly, yearly, and hourly collision trends

**Technologies Used**
Python
PySpark
AWS Cloud Services
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

**Key Insights**
Most collisions fall into lower-severity categories, while severe collisions are relatively rare but high impact.
Clear weather accounts for the highest number of collisions, followed by cloudy and rainy conditions.
Collision victims are predominantly young adults between 18 and 25 years of age.
Friday records the highest collision frequency, while weekends experience fewer collisions.
Los Angeles County is the primary collision hotspot, significantly exceeding other counties in collision volume.
Peak collision activity occurs between 2 PM and 6 PM, indicating increased risk during high traffic periods.
Poor lighting conditions increase the proportion of injury-related collisions.
Weather and road surface conditions influence collision severity more than collision frequency.

**Results**
The analysis successfully identified collision hotspots, peak accident periods, and environmental factors influencing collision severity. 
The findings provide actionable recommendations for improving road safety through infrastructure enhancements, targeted traffic monitoring, improved lighting, optimized signal timings, and data-driven policy decisions. 
Additionally, the project highlights opportunities for developing predictive models to forecast collision hotspots and support proactive traffic management strategies
