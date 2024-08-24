# MoonLight Energy Solutions: Strategic Solar Investment Analysis
Project Overview
This repository contains the Python-based analysis conducted for MoonLight Energy Solutions, focusing on enhancing operational efficiency and sustainability through targeted solar investments. The analysis aims to identify high-potential regions for solar installation by examining environmental measurement data provided by the engineering team.

# Objective
The goal of this analysis is to perform a thorough exploratory data analysis (EDA) and statistical assessment to uncover key trends and valuable insights. These insights will inform a data-driven strategy report, which will guide MoonLight Energy Solutions in making informed decisions aligned with its long-term sustainability goals.

# Exploratory Data Analysis (EDA)
During the EDA phase, the following analyses are performed on the solar energy dataset:

 [Click Here to view the Exploratory-Data-Analysis.ipynb file](https://github.com/nolawit-fant/solar-radaition/blob/main/notebooks/EDA.ipynb)

Summary Statistics: Calculate descriptive statistics such as mean, median, and standard deviation for each numeric column in order to understand the data distribution.

Data Quality Check: Identify missing values, outliers, or incorrect entries in columns such as GHI, DNI, DHI, and others.

Time Series Analysis: Analyze how variables like GHI, DNI, DHI, and Tamb change over time. Plotting these metrics across the 'Timestamp' can help identify patterns or anomalies.

Correlation Analysis: Determine the correlation between different variables, such as solar radiation components (GHI, DHI, DNI) and temperature measures (TModA, TModB), to uncover relationships.

Wind Analysis: Explore wind speed (WS, WSgust, WSstdev) and wind direction (WD, WDstdev) data to identify trends or notable wind events.

Temperature Analysis: Compare module temperatures (TModA, TModB) with ambient temperature (Tamb) to understand their relationship or variation under different conditions.

Histograms: Create histograms for variables like GHI, DNI, DHI, WS, and temperatures to visualize their frequency distribution.

Box Plots: Use box plots to examine the spread and presence of outliers in the solar radiation and temperature data.

Scatter Plots: Generate scatter plots to explore relationships between pairs of variables, such as GHI vs. Tamb or WS vs. WSgust.

# Technologies Used
Python
Pandas
Matplotlib/Seaborn for visualization
Jupyter Notebook
# How to Use

To set up the Python environment for this project, follow the steps below:

1. **Clone the repository to your local machine:**

   ```bash
   git clone https://github.com/nolawit-fant/solar-radiation

2. **Create a virtual environment specific to this project. Use the appropriate command for your operating system:**

For Windows:


(python -m venv venv
venv\Scripts\activate)

For Linux and macOS:
(python3 -m venv venv
source venv/bin/activate)

3. **Install the required packages.**
   
4.**Run the analysis and review the strategy report for actionable insights.**


# Dashboard development
Streamlit is a powerful Python library used for building interactive web applications. In this project, Streamlit is used to develop a dashboard for visualizing and exploring the solar energy data.The dashbboard is built in such a way that it provides an intuitive interface to interact with the analyzed data and gain insights.

[click here to view the steamlit dashboard](https://solar-radaition.streamlit.app/)
