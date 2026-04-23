## IN THE WORKS

# Qualite_de_l_air_en_Ontario_2015-2024
Projet en binôme pour SED 1516 - Visualisation et analytique des données  
  
**Note :** Ce dépôt a été créé et maintenu par moi après la fin du projet du cours. Il s’agit d’une organisation personnelle et indépendante du travail, à des fins de partage et de portfolio.

## Fichiers et dossiers
- **`livrable 1`:**
- **`livrable 2`:**
- **`livrable 2`:**
- **`livrable 2`:**
  
## Contributions
- expliquer dans chauqe rapport PDF
  
## Utilisation
download Excel files from `data_raw` in `livrable 1` for all raw data
download Excel files from `data_ongoing` in `livrable 2` for all data manipuation and some simple visualisation
download Power BI files from `livrable 3` for moreindepth visualisation
dowload any PDF report  tfor explantion etc..
  
## Source de données
totue les donne viene du site web = [Qualité de l'air Ontario](https://www.qualitedelairontario.com/)

---
---
# Multi-city Climate Dashboard
Pair project for SDS 3786 - Data Science Laboratory (French section of SDS 3386)  
  
**Note :** This repository was created and maintained by me after the completion of the course project. It serves as a personal, independent organization of the work for sharing and portfolio purposes. 

## Files and Folders
- **`code`**
  - **`Arielle`** = code written by my partner  
    - `IMPUTATION_CLUSTERING_TIME_SERIES_SDS3786_Groupe5.ipynb` = code for the sections: imputation, clustering and time series
  - **`Dashinee`** = code written by me  
    - `project_EDA_SDS3786_Groupe5.ipynb` = exploratory data analysis  
    - `project_Multi_ville_Cartes_SDS3786_Groupe5.ipynb` = Multi-city analysis and maps  
    - `project_dashboard_SDS3786_Groupe5.ipynb` = dashboard  
- **`data`** = datasets
  - `ville_2.csv` = files whose columns were standardized directly in Excel
  - `ville_4.csv` = files with snow (Ottawa/Vancouver) and pressure (other cities) data removed to match columns across all 6 datasets
  - `ville_clean.csv` = imputed files
- **`docs`**
  - `Étape1_Proposition_de_projet_SDS3786_Groupe5.pdf` = initial project proposal  
  - `Étape2_Presentation_du_projet_SDS3786_Groupe5.pdf` = in-class presentation slides  
  - `project_rapport_SDS3786_Groupe5.pdf` = report used for final video presentation
  - `revised_activity_table.png` = screenshot of the revised activity table, with minor changes from the initial (Step 1) and final report versions

## Contributions
- Dashinee:
  - **Data Collection**: Downloaded the 6 CSV files (Ottawa (Canada), Vancouver (Canada), Cotonou (Benin), Parakou (Benin), Plaisance (Mauritius), Vacoas (Mauritius))
  - **Cleaning and Merging**: Standardized columns, formatted dates, removed unused columns
  - **Exploratory Data Analysis (EDA)**: Visualizations and calculation of descriptive statistics for all cities
  - **Multi-city and Maps**: Comparative charts, maps with colors/clusters, tooltips, city-specific indicators
  - **Python Implementation (Panel/HvPlot)**: Coded the dashboard and integrated visualizations
  - **Testing and Adjustments**: Checked interactivity, overall consistency, and made adjustments
  - **Final Report (collaborative work)**: Writing the PDF (summary, screenshots, references)

- Arielle:
  - **Imputation**: Rolling mean / seasonal imputation for missing values
  - **Clustering**: Created climate groups (K-Means or DBSCAN) for all cities
  - **Time Series & Forecasting**: Analysis of 2020-2024 trends and forecasts for upcoming months/years
  - **Dashboard Design**: Choice of widgets, layout, multi-city interactivity
  - **Final Report (collaborative work)**: Writing the PDF (summary, screenshots, references)

## Usage
This project was developed using Google Colab.  
To reproduce the results:
1. Download the code and datasets  
2. Upload the data files to your Colab environment  
3. Run the notebooks  

## Data Sources
- **Ottawa and Vancouver =** CSV files were downloaded for the years 2020 to 2024 (one file per year) from the following pages (data for 2020): [Ottawa](https://climate.weather.gc.ca/climate_data/daily_data_e.html?hlyRange=2011-12-14%7C2025-03-15&dlyRange=2011-12-15%7C2025-03-14&mlyRange=%7C&StationID=49568&Prov=ON&urlExtension=_e.html&searchType=stnName&optLimit=yearRange&StartYear=1840&EndYear=2025&selRowPerPage=25&Line=14&searchMethod=contains&Month=1&Day=15&txtStationName=ottawa&timeframe=2&Year=2020) and [Vancouver](https://climate.weather.gc.ca/climate_data/daily_data_e.html?hlyRange=2013-06-11%7C2025-03-15&dlyRange=2013-06-13%7C2025-03-15&mlyRange=%7C&StationID=51442&Prov=BC&urlExtension=_e.html&searchType=stnName&optLimit=yearRange&StartYear=1840&EndYear=2025&selRowPerPage=25&Line=41&searchMethod=contains&txtStationName=vancouver&timeframe=2&Day=15&Year=2020&Month=1), then combined in Excel to obtain a single complete database covering the period 2020-2024 (Ottawa = OTTAWA INTL A, Vancouver = VANCOUVER INTL A).
- **Plaisance, Vacoas, Cotonou and Parakou =** The CSV files were downloaded by selecting the period from 01/01/2020 to 12/31/2024 from the following pages : [Plaisance](https://meteostat.net/en/station/61990?t=2020-01-01/2024-12-31&utm), [Vacoas](https://meteostat.net/en/place/mu/vacoas?s=61995&t=2026-01-05/2026-01-12), [Cotonou](https://meteostat.net/en/place/bj/cotonou?s=65344&t=2026-01-05/2026-01-12) and [Parakou](https://meteostat.net/en/place/bj/parakou?s=65330&t=2026-01-05/2026-01-12).

---
---
*Honours Bachelor of Science in Statistics - University of Ottawa*  
*Contact: dashinee.parmanum@gmail.com*  
*LinkedIn: https://www.linkedin.com/in/dashinee-parmanum/*
