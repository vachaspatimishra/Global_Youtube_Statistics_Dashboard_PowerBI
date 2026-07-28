# 📊 Global YouTube Statistics Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive **Power BI Dashboard** built using a Global YouTube Statistics dataset containing information about 1000+ YouTube channels. The dashboard provides insights into subscriber count, video views, uploads, channel categories and country-wise performance.

The objective of this project is to demonstrate data cleaning, transformation, data modeling, DAX measures and interactive dashboard design for business intelligence reporting.

---

## 📂 Dataset Information

### Raw Data

* **Dataset Records:** **1,006**
* **Columns:** **29**
* **Unique YouTube Channels:** **995**
* **Countries Represented:** **50**
* **Content Categories:** **18**
  
### Cleaned Data

* **839 Records**

---

# 🧹 Data Cleaning & Transformation (Power Query)

The raw dataset contained several inconsistencies that were cleaned before visualization.

### Cleaning Steps Performed

* Replaced **invalid/special characters** with **Null** values.
* Replaced missing numerical values with **0** wherever appropriate.
* Corrected inconsistent text values.
* Changed data types for all columns (Text, Whole Number, Decimal, Date).
* Standardized country and category values.
* Checked for duplicate records.
* Verified null values across important fields.
* Renamed columns for better readability.
* Loaded the cleaned dataset into the Power BI Data Model.

---

# 📊 Dashboard KPIs

The dashboard includes important business KPIs such as:

* Total Subscribers
* Total Video Views
* Total Uploads
* Total YouTube Channels
* Average Category Views

---

# 📈 Dashboard Visualizations

* Top 10 Channels by Subscribers **Bar Chart**
* Top 5 Countries by Channels **Tree Map**
* Total Yearly Views **Line Chart**
* Country-wise Subscribers **Map**
* Subscribers vs Views **Scatter Chart**
* Top 5 Categories by Subscribers **Donut Chart**
* Interactive Filters (Country, Category, Year)

---

# 🔍 Key Insights

### Dashboard Overview

* The dashboard analyzes **839 YouTube channels** after data cleaning and transformation in Power Query.
* These channels collectively account for:
    * **19.3 Billion Subscribers**
    * **9.6 Trillion Total Views**
    * **9 Million Total Video Uploads**
* **The average views across all categories is 504.9 Billion**.

### Category Insights

* **Music** is the largest contributor, accounting for **33.8%** of total subscribers.
* **Entertainment** closely follows with **31.4%** of total subscribers.
* Together, **Music and Entertainment contribute approximately 65.2% of all subscribers**, making them the dominant content categories on YouTube.
* **People & Blogs** contributes **14.7%**, followed by **Gaming (11.5%)** and **Comedy (8.6%)**.
* The scatter plot also shows that **Music and Entertainment channels achieve the highest combination of subscribers and total views**, significantly outperforming   other categories.

### Country Insights

* **United States** has the **highest number of channels** in the dataset with **301 channels**.
* **India** ranks **second with 166 channels**, followed by **Brazil with 60 channels**.
* **United Kingdom and Mexico** are also among the top five countries represented.
* The geographic distribution indicates that the **majority of high-performing YouTube channels originate from North America and Asia**.

These five countries contribute the majority of subscribers represented in the dataset.

### Channel Insights

* **T-Series** is the **most subscribed channel** with **245 Million** subscribers.
* The second largest channel has 170 Million subscribers, followed by MrBeast with 166 Million subscribers.
* The remaining channels in the Top 10 subscriber list range from 97 Million to 162 Million subscribers, highlighting the concentration of audience among the largest creators.

### Trend Analysis

* Total YouTube views have grown significantly over time, reaching a peak of approximately **1.37 Trillion** views in a single year before showing fluctuations in more recent years.
* The trend indicates rapid platform growth during the 2000s and early 2010s, followed by stabilization in recent years.

---

# 🛠 Tools

* Microsoft Power BI
* Power Query
* DAX
* Data Modeling

---

# 💡 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Power Query
* DAX Measures
* KPI Design
* Dashboard Design
* Data Visualization
* Business Intelligence
* Interactive Reporting

---

⭐ If you found this project useful, consider giving it a star!
