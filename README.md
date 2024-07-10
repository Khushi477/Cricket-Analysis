# Cricket-Analysis

## Overview
This project aims to analyze cricket data to derive meaningful insights about players' performance and to suggest a strong final XI that can compete against any team in the world. The project involves web scraping, data preprocessing, and visualization using PowerBI.

## Project Workflow
1. **Web Scraping**: Data was scraped from a cricket website "https://www.espncricinfo.com/" and saved into JSON files. The website was scrapped using an application Bright Data.
   
2. **Data Preprocessing**: Using Python and Jupyter Notebooks, the data was cleaned, processed, and converted into CSV files.
   
3. **Data Visualization**: The processed data was uploaded to PowerBI to create interactive dashboards for analyzing batters, bowlers, and other metrics. The csv files were loaded and transformed on PowerBI and various analysis were carried out based on several metrics.
   
4. **Final XI Selection**: Based on the analysis, a final XI team was suggested to form a strong lineup against any team in the world.

## Reguirements
   Python 3.x
   Jupyter Notebook
   PowerBI
   Excel
   Bright Data

## Usage
**Web Scraping**
1. Run the web_scraping_codes on Bright data to scrape cricket data from the website.
2. The scraped data will be saved as JSON files.
   
**Data Preprocessing**
1. Run the Preprocessing Cricket Analysis.ipynb notebook to preprocess the JSON data.
2. The processed data will be saved as CSV files.

**Data Analysis & Visualization**
1. Open PowerBI and import the CSV files from the directory.
2. Use the provided PowerBI template or create your own dashboards to analyze the data.
3. Explore the dashboards to view insights on batters, bowlers, and the final XI selection.

## Project Structure
cricket-analysis/
├── data/
|   ├── web_scraping_codes.ipynb
│   ├── json/
├── notebooks/
│   └── data_preprocessing.ipynb
|   └── csv/
├── dashboards/
│   └── cricket_analysis.pbix
├── README.md


