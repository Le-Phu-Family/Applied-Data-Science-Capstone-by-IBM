# SpaceX Falcon 9 Landing Prediction

Capstone project for the IBM Applied Data Science Specialization.

This project investigates SpaceX Falcon 9 launch data to answer a practical business question:

**Can we predict whether the first stage will land successfully?**

Accurate landing prediction matters because first-stage reuse is one of the biggest drivers of launch cost reduction. The analysis combines data collection, wrangling, exploratory analysis, interactive visualization, and machine learning.

## Project Highlights

- Collected launch data from APIs and web scraping workflows
- Cleaned and transformed raw records into analysis-ready datasets
- Explored launch outcomes with SQL, statistics, and visual analytics
- Built interactive geospatial visuals for launch site insights
- Trained classification models to predict first-stage landing success

## Repository Structure

```text
.
|-- collect the data/
|   |-- jupyter-labs-spacex-data-collection-api.ipynb
|   `-- jupyter-labs-webscraping.ipynb
|-- data/
|   |-- dataset_part_1.csv
|   `-- spacex_web_scraped_1-Copy1.csv
|-- eda/
|   |-- edadataviz.ipynb
|   |-- jupyter-labs-eda-sql-coursera_sqllite.ipynb
|   `-- labs-jupyter-spacex-Data wrangling.ipynb
|-- interactive visual/
|   |-- DV0101EN-Exercise-Generating-Maps-in-Python.ipynb
|   `-- lab_jupyter_launch_site_location.ipynb
|-- predictive analysis/
|   `-- SpaceX_Machine Learning Prediction_Part_5 (1).ipynb
`-- report/
	 |-- assets/
	 |   |-- analysis_summary.json
	 |   |-- folium_map_1.html
	 |   |-- folium_map_2.html
	 |   `-- folium_map_3.html
```

## End-to-End Workflow

1. **Data Collection**
	- Gathered SpaceX launch records via API and web scraping notebooks.
2. **Data Wrangling**
	- Standardized fields, handled missing values, and prepared modeling features.
3. **Exploratory Data Analysis (EDA)**
	- Analyzed launch outcomes by payload, booster version, orbit, and launch site.
4. **Interactive Visual Analytics**
	- Built map-based visuals to identify spatial patterns and launch behavior.
5. **Predictive Modeling**
	- Trained and evaluated machine learning classifiers for landing success prediction.

## Tools and Libraries

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- folium
- requests, BeautifulSoup
- scikit-learn
- SQL (notebook-based analysis)

## How To Run

1. Clone this repository.
2. Create and activate a Python environment.
3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn folium requests beautifulsoup4 scikit-learn ipython-sql prettytable
```

4. Open notebooks in this recommended order:
	- `collect the data/`
	- `eda/`
	- `interactive visual/`
	- `predictive analysis/`
	- `report/`

## Outputs

- Cleaned and intermediate datasets stored in `data/`
- Analysis visuals and map artifacts stored in `report/assets/`
- Final modeling notebook in `predictive analysis/`

## Why This Project Matters

This capstone demonstrates an end-to-end data science workflow from raw data ingestion to predictive modeling and reporting. It highlights practical skills in:

- data acquisition from multiple sources
- feature engineering and analytical reasoning
- model building and evaluation
- storytelling with visual and geospatial insights

## Author

IBM Applied Data Science Capstone learner project.