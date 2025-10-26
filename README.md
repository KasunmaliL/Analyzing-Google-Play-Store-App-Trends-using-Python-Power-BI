# Analyzing-Google-Play-Store-App-Trends-using-Python-Power-BI

Day 1 – Data Loading & Cleaning

Tools: Python, Pandas, NumPy
Key Tasks:
* Imported dataset using kagglehub from Kaggle.
* Handled missing values and removed duplicate entries.
* Cleaned text-based numeric columns (Price, Installs, Reviews).
* Converted data types and filtered invalid ratings (Rating > 5).
* Added a derived column isPaid → 1 = Paid, 0 = Free.
* Saved cleaned dataset as cleaned_playstore.csv.

Day 2 – Exploratory Data Analysis (EDA)

Tools: Matplotlib, Seaborn
Key Tasks:
* Loaded cleaned data for visual exploration.
* Identified top app categories and their distribution.
* Visualized rating trends using bar plots, histograms, and scatter plots.
* Performed correlation analysis between Rating, Installs, Reviews, and Price.
* Exported analysis summary as eda_summary.csv.

Key Insights:
* Most popular categories: Family, Game, and Tools.
* Paid apps have slightly higher ratings than free apps.
* Reviews are highly correlated with installs — indicating user engagement drives downloads.
* Price shows weak negative correlation with installs.
* Most apps have ratings between 4.0 and 4.5, showing high user satisfaction.

Day 3 – Power BI Dashboard

Tool: Microsoft Power BI 
Created Visuals:
* Bar Chart: Top 10 app categories by count
* Donut Chart: Free vs Paid app distribution
* Line Chart: Average rating by category
* KPI Cards: Average Rating, Total Installs

What I Learned: 
* End-to-end data analytics workflow using Python and Power BI.
* Advanced data cleaning and transformation with Pandas.
* Creating data visualizations and identifying patterns in large datasets.
* Building interactive Power BI dashboards with KPIs and visuals.
* Translating raw data into business insights and actionable takeaways.

Tools & Technologies
* Category	          Tools Used
* Data Cleaning	      Python, Pandas, NumPy
* Visualization	      Matplotlib, Seaborn
* Dashboard	          Microsoft Power BI
* Dataset	            Google Play Store Apps – Kaggle
