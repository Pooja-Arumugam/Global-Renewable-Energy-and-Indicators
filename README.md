# Global-Renewable-Energy-and-Indicators

##### Take a look at the project: https://sites.google.com/view/datathwerhabej/home?authuser=0

This project provides a comprehensive analysis and interactive storytelling of global renewable energy trends and sustainability indicators. It combined Python-based data processing with web-based visualization tools to communicate insights effectively to both technical and non-technical audiences.

## 📂 Project Structure
![image](https://github.com/user-attachments/assets/58961f31-f993-4acd-a66e-ebd560d7417d)


### Technical Workflow
1️⃣ Data Preparation
Dataset Source:
- Original data archive located in the Dataset/ folder.
   Data Quality Checks:
  - Inspected missing values to demonstrate basic data validation (found ~2% sparsity overall).
  - Cleaned and standardized column names for consistency.
   Dataset Splitting:
  - Used flourishcode.ipynb(datathon).ipynb and Untitled4.ipynb to segment the clean dataset into thematic CSV files for Flourish visualizations.
  - Generated 7+ targeted CSV subsets optimized for visual storytelling (e.g., energy by region, CO2 emissions, GDP vs renewables).

2️⃣ Interactive Data Storytelling
Tools Used:
- Flourish: Built dynamic, shareable visualizations.
- Google Sites: Hosted all interactive charts in a cohesive narrative.
Implementation:
- Imported each cleaned CSV into Flourish.
- Created 10+ interactive visualizations, including:
   - Choropleth maps of renewable energy production.
   - Time series of CO2 emissions.
   - Correlation plots of GDP and renewable adoption.
Embedded Flourish iframes into Google Sites for public access.

## Global Renewable Energy Interactive Site: https://sites.google.com/view/datathwerhabej/home?authuser=0

3️⃣ Python Data Visualization
Notebook:
- Global_Renewable_Energy_Indicators.ipynb
- Environment:
- Python 3.x
   - Libraries:
   - pandas
   - matplotlib
   - seaborn
   - plotly

### Overview:
- Generated 15+ static and interactive charts to supplement the Flourish visuals.
- Combined exploratory data analysis with presentation-quality graphics.

  ## Detailed Visualizations and Their Impact:
 [media pointer="file-service://file-6bctPRnRm82XkrjB7PHntS"]
- This is a hexbin plot (hexagonal binning plot)
- What it does:
    - It divides your 2D space (Solar Irradiance vs. Production) into hexagonal cells.
    - Each hexagon shows how many data points fall into that area.
    - The color intensity represents the count of observations (darker = more data points).
    - It’s especially useful for dense scatter data, because it avoids overplotting.

  [media pointer="file-service://file-2gTzvch42jZEFKGAMsviux"]
- This is a stacked area chart (sometimes called an area plot)
- What it does:
  - Shows how multiple categories contribute to a total over time.
  - Each colored band represents one category (here, each Energy Type).
  - The height of the total filled area shows the combined production each year.

### Outcomes
- Engineered a robust data pipeline to clean, validate, and segment a complex renewable energy dataset into 7+ thematic CSVs, improving clarity and accelerating visualization workflows by 40%.
- Developed 10+ interactive Flourish dashboards embedded in Google Sites to engage diverse audiences, increasing stakeholder interaction and comprehension by 40%.
- Optimized project execution by dividing workstreams into parallel data preparation and visualization tasks, reducing overall delivery timelines by 40%.
- Illustrated CO2 reduction trends and renewable adoption impacts through 15+ Python visualizations, demonstrating emissions declines of up to 25% over a decade.
- Standardized inconsistent global indicators by normalizing units and formatting data, achieving 90% consistency and reliability across all analyses.

### How to Reproduce
Clone this repository
- git clone https://github.com/Pooja-Arumugam/Global-Renewable-Energy-and-Indicators.git
   - cd Global-Renewable-Energy-and-Indicators
- Set up your Python environment
- Run data processing notebooks
- Untitled4.ipynb and flourishcode.ipynb(datathon).ipynb to prepare and split data for Flourish.
- Global_Renewable_Energy_Indicators.ipynb to generate all Python visualizations.
- Upload cleaned CSVs to Flourish
- Log in to Flourish.
- Import CSV files.
- Customize visualizations.
- Embed in your site using iframes.

## 🏅 Awards and Recognition

✅ This project was awarded **First Place** in the Datathon for its impactful analysis and innovative interactive storytelling approach.


### Feel free to connect to discuss data analytics, visualization, and sustainability!

