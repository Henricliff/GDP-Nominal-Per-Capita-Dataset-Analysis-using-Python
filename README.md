GDP (Nominal) Per Capita Dataset Analysis
This repository contains a dataset of GDP (Nominal) per capita for various countries and provides Python scripts to analyze and visualize the data using Pandas.

📊 Project Overview
This project aims to explore and analyze the nominal GDP per capita across different countries using Python. It includes data cleaning, basic statistical analysis, and visualization.

🧰 Technologies Used
Python 3.x

Pandas

Matplotlib / Seaborn (for visualization)

Jupyter Notebook (optional for interactive analysis)

📁 Dataset
The dataset consists of GDP (Nominal) per capita figures for countries worldwide.

Data source: [World Bank / IMF / other source] (replace with actual source if applicable)

The data file is included in the repository as gdp_nominal_per_capita.csv

🔍 Features
Load and clean GDP dataset using Pandas

Summary statistics (mean, median, max, min GDP per capita)

Visualization of GDP distribution across countries

Trend analysis over years (if dataset is time-series)

🛠️ Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/gdp-nominal-per-capita.git
cd gdp-nominal-per-capita
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Run the analysis script:

bash
Copy
Edit
python analyze_gdp.py
or open analysis_notebook.ipynb with Jupyter Notebook for interactive exploration.

📂 File Structure
bash
Copy
Edit
├── data/
│   └── gdp_nominal_per_capita.csv
├── analyze_gdp.py
├── analysis_notebook.ipynb
├── README.md
Example Code Snippet
python
Copy
Edit
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load dataset
df = pd.read_csv('data/gdp_nominal_per_capita.csv')

# Display summary statistics
print(df['GDP_per_capita'].describe())

# Plot distribution
sns.histplot(df['GDP_per_capita'], bins=30)
plt.title('GDP Nominal Per Capita Distribution')
plt.xlabel('GDP per Capita (USD)')
plt.ylabel('Frequency')
plt.show()
📚 References
World Bank GDP Data

Pandas Documentation

Matplotlib Documentation

Seaborn Documentation
