# Netflix_content_analysis
This project performs an exploratory data analysis (EDA) on the Netflix Movies and TV Shows dataset. The goal is to uncover trends in content additions, understand the distribution of media types, and analyze Netflix's growth strategy over the last decade

-Language:
Python 3.x (Anaconda Environment)
Libraries: * Pandas: Data manipulation and cleaning.
Seaborn & Matplotlib: Data visualization.
Jupyter Notebook: Interactive analysis.

-How to Run
1)Clone the repository or download the files.
2)Ensure you have Anaconda or Python installed.
3)Install dependencies:
  -pip install pandas seaborn matplotlib
4)Open Netflix_Analysis.ipynb in Jupyter Notebook.
5)Run the cells to see the automated cleaning and visualization in action.

-Data Cleaning Process
To ensure the analysis was accurate, the following steps were taken:
  -Missing Values: Filled missing director, cast, and country data with the placeholder "Unknown".
  -Row Removal: Dropped a small percentage of rows with missing date_added to maintain timeline integrity.
  -Type Conversion: Converted date strings into datetime objects for time-series analysis.
  -Feature Engineering: Extracted year_added to track growth trends.
