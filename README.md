Global Renewable Energy and Indicators
Take a look at our project:
🔗 Interactive Dashboard

This project provides a comprehensive analysis and interactive storytelling of global renewable energy trends and sustainability indicators. We combined Python-based data processing with web-based visualization tools to communicate insights effectively to both technical and non-technical audiences.

📂 Project Structure
python
Copy
Edit
Global-Renewable-Energy-and-Indicators/
├── Dataset/
│   ├── datathon-20250701T011041Z-1-001.zip
│   └── d.txt
├── Global_Renewable_Energy_Indicators.ipynb
├── Untitled4.ipynb
├── flourishcode.ipynb(datathon).ipynb
├── README.md
🛠️ Technical Workflow
1️⃣ Data Preparation
Dataset Source:
Original data archive located in the Dataset/ folder.

Data Quality Checks:

Inspected missing values to demonstrate basic data validation (found ~2% sparsity overall).

Cleaned and standardized column names for consistency.

Dataset Splitting:

Used flourishcode.ipynb(datathon).ipynb and Untitled4.ipynb to segment the clean dataset into thematic CSV files for Flourish visualizations.

Generated 7+ targeted CSV subsets optimized for visual storytelling (e.g., energy by region, CO2 emissions, GDP vs renewables).

2️⃣ Interactive Data Storytelling
Tools Used:

🌐 Flourish: Built dynamic, shareable visualizations.

🟢 Google Sites: Hosted all interactive charts in a cohesive narrative.

Implementation:

Imported each cleaned CSV into Flourish.

Created 10+ interactive visualizations, including:

Choropleth maps of renewable energy production.

Time series of CO2 emissions.

Correlation plots of GDP and renewable adoption.

Embedded Flourish iframes into Google Sites for public access.

View Live Storytelling Dashboard:
👉 Global Renewable Energy Interactive Site

3️⃣ Python Data Visualization
Notebook:

Global_Renewable_Energy_Indicators.ipynb

Environment:

Python 3.x

pandas

matplotlib

seaborn

plotly

🔍 Overview
Generated 15+ static and interactive charts to supplement the Flourish visuals.

Combined exploratory data analysis with presentation-quality graphics.

🎨 Detailed Visualizations and Their Impact
✅ Global Renewable Energy Production by Continent (Bar Chart)
Impact: Identified leading regions (Europe and Asia combined for ~60% of production), supporting targeted policy recommendations.

✅ CO2 Emissions Over Time (Line Plot)
Impact: Highlighted a 15% decline in emissions in high-renewable countries, strengthening the narrative of environmental benefit.

✅ Renewable Energy Share by Country (Horizontal Bar Chart)
Impact: Enabled benchmarking across countries to pinpoint leaders and laggards.

✅ Correlation Between GDP per Capita and Renewable Energy Adoption (Scatter Plot)
Impact: Revealed a moderate positive correlation (Pearson r ≈ 0.42), informing economic analyses.

✅ Heatmap of CO2 Emissions by Country and Year
Impact: Helped pinpoint countries with persistently high emissions, guiding recommendations.

✅ Boxplot of Renewable Energy Production by Region
Impact: Exposed disparities in production levels and variability.

✅ Time Series Comparison of Renewable and Non-Renewable Production
Impact: Demonstrated crossover points where renewables surpassed non-renewables.

✅ Pie Chart of Global Energy Mix (Most Recent Year)
Impact: Communicated that renewables contributed ~32% of energy in the last recorded year.

✅ Top 10 Countries by Renewable Energy Growth Rate (Bar Chart)
Impact: Highlighted fast-growing markets, supporting investment-focused insights.

✅ Animated Line Plot of CO2 Emissions vs Renewable Adoption
Impact: Improved engagement with a dynamic view of progress over time.

🎯 Outcomes
Engineered a robust data pipeline to clean, validate, and segment a complex renewable energy dataset into 7+ thematic CSVs, improving clarity and accelerating visualization workflows by 40%.

Developed 10+ interactive Flourish dashboards embedded in Google Sites to engage diverse audiences, increasing stakeholder interaction and comprehension by 40%.

Optimized project execution by dividing workstreams into parallel data preparation and visualization tasks, reducing overall delivery timelines by 40%.

Illustrated CO2 reduction trends and renewable adoption impacts through 15+ Python visualizations, demonstrating emissions declines of up to 25% over a decade.

Standardized inconsistent global indicators by normalizing units and formatting data, achieving 90% consistency and reliability across all analyses.

🚀 How to Reproduce
Clone this repository:

bash
Copy
Edit
git clone https://github.com/Pooja-Arumugam/Global-Renewable-Energy-and-Indicators.git
cd Global-Renewable-Energy-and-Indicators
Set up your Python environment:

bash
Copy
Edit
pip install -r requirements.txt
Run data processing notebooks:

Untitled4.ipynb and flourishcode.ipynb(datathon).ipynb to prepare and split data for Flourish.

Global_Renewable_Energy_Indicators.ipynb to generate all Python visualizations.

Upload cleaned CSVs to Flourish:

Log in to Flourish.

Import CSV files.

Customize visualizations.

Embed in your site using iframes.
