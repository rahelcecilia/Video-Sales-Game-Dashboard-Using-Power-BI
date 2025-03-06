# Video Sales Game Dashboard Using Power BI

Analyzed Kaggle's Video Game Sales dataset to understand video game sales trends by genre, platform and region. <br>
Dataset : https://www.kaggle.com/datasets/gregorut/videogamesales?resource=download

### Technologies Used:
<li>Python (Pandas) – Data Cleaning, Handling Missing & Duplicate Values</li> <br>


<pre>import pandas as pd 
df = pd.read_csv('vgsales.csv') <br>
<strong> # Missing Values</strong>
df.isna().sum() <br>
<strong> # Duplicate Values</strong>
duplicate_rows = df[df.duplicated()]<br>
<strong> #Export</strong>
df.to_excel("vgsales.xlsx") </pre>

<li>Power BI – DAX, Filter, Chart (Bar, Pie, Line)</li>

### Features and Analysis:
<li>Displayed 15 interactive visualizations to explore video game sales trends.</li>
<li>Year Filter for analyzing sales based on specific periods.</li> 
<li>Top-Selling Games by region (Japan, North America, Europe, and others).</li> 
<li>Revenue Analysis by genre using a pie chart.</li> <li>Global Sales Trends by platform using a line chart.</li> 
<li>Ranking of Best-Selling Games globally with a bar chart.</li>

### Results and Insights:
<li>Identified the most dominant genres and platforms across different regions.</li> 
<li>Analyzed video game sales trends over time.</li> 
<li>Provided insights for the gaming industry to refine marketing strategies and product development.</li>
