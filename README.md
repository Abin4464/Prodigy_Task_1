# Prodigy_Task_1
📊 Project Overview
This task focuses on visualizing the distribution of population across countries using a bar chart. Specifically, the project displays the top 10 most populous countries in the year 2023 based on World Bank data.

📁 Dataset
Source: World Bank – Total Population

File: API_SP.POP.TOTL_DS2_en_csv_v2_394221.csv

🧹 Data Processing
Loaded the dataset and skipped metadata rows.

Filtered out data for the year 2023.

Removed countries with missing population data.

Sorted and selected the top 10 countries by population.

📈 Visualization
A bar chart is plotted using matplotlib.

The chart includes country names on the X-axis and population values on the Y-axis.

The plot is titled “Top 10 Most Populous Countries (2023)” with rotated X-tick labels for better readability.

🛠️ Libraries Used
pandas for data manipulation

matplotlib for plotting

🚀 How to Run
Ensure you have Python installed.

Install required libraries using:

bash
Copy
Edit
pip install pandas matplotlib
Run the script:

bash
Copy
Edit
python script_name.py
📌 Output
The script will display a bar chart showing the top 10 most populous countries in 2023.
