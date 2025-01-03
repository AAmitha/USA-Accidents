USA Accidents Analysis - Exploratory Data Analysis (EDA)

Overview:
This project focuses on Exploratory Data Analysis (EDA) of the US Accidents dataset. The dataset contains information on traffic accidents occurring across the United States, providing valuable insights into accident patterns, trends, and geographical distributions.

Project Goals:
Perform data preparation, cleaning, and exploration.
Analyze accident trends by time, location, and other key factors.
Identify patterns that can help policymakers, urban planners, and traffic authorities improve road safety.

Dataset: https://drive.google.com/file/d/1XrQHy5Jb4z4bQAQt3Ay_tRHwvYIE9f1Q/view?usp=sharing
The dataset used for this analysis is sourced from US Accidents Database. It includes columns like:

Start_Time: Date and time when the accident occurred.
End_Time: Date and time when the accident ended.
Start_Lat and Start_Lng: Geographical coordinates for the accident location.
City, State, County: Information about the accident's location.
Source: Reporting source of the data.
Severity: The severity of the accident.
Additional columns with detailed information on weather, traffic, and road conditions.
Methodology
Data Preparation & Cleaning:

Cleaned and handled missing values.
Converted Start_Time to datetime format for better analysis.
Filtered and processed numerical and categorical data.
Exploratory Data Analysis (EDA):

Analyzed accident patterns by location, time, and day of the week.
Used visualizations such as histograms, scatter plots, and heatmaps to identify accident-prone areas.
Investigated temporal patterns in accident frequency.
Key Insights:

Most accidents occur during rush hours (6–10 AM and 3–6 PM).
Weekend accidents peak between 10 AM and 3 PM.
A significant number of cities report only one accident, raising data quality concerns.
Potential inconsistencies found in the Source1 data suggest further investigation.
Tools & Libraries Used
Python: Pandas, NumPy, Seaborn, Matplotlib for data manipulation and visualization.
Folium: Used for creating interactive heatmaps to visualize accident density.
Git/GitHub: To manage and version control the project.
Repository Structure
USAccidents.csv: The cleaned dataset used for analysis.
US_Accidents_EDA.ipynb: Jupyter Notebook containing all the analysis and visualizations.
README.md: This file, providing a project overview and instructions.
Contributions
Feel free to fork this repository, explore, and contribute if you'd like to expand on the analysis or improve any part of the project.

Questions & Contact
For any questions or collaborations, please feel free to reach out:

Email: amitha.akepati00@gmail.com
LinkedIn: https://www.linkedin.com/in/amitha-akepati/
Thank you for exploring the US Accidents dataset!
