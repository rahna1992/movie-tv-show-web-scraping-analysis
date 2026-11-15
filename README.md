# Movie & TV Show Data Analysis Using Python Web Scraping

## Project Overview

This project focuses on collecting, cleaning, analysing, and visualising movie and TV show information from [JustWatch India](https://www.justwatch.com/in/).

Python web scraping techniques were used to extract movie and TV show details from website HTML. The collected data was processed using Pandas to explore IMDb ratings, genres, release years, and streaming platform availability.

## Objectives

- Extract movie and TV show information using web scraping.
- Collect movie titles, release years, genres, IMDb ratings, and streaming platforms.
- Clean and organise scraped data using Pandas.
- Analyse IMDb ratings and genre distribution.
- Identify popular streaming platforms.
- Export datasets into CSV files.

## Tools & Technologies

- **Programming Language:** Python
- **Web Scraping:** Requests, BeautifulSoup
- **Data Manipulation:** Pandas, NumPy
- **Data Visualisation:** Matplotlib, WordCloud
- **Environment:** Google Colab
- **Data Storage:** CSV

## Project Workflow

### 1. Data Collection (Web Scraping)

Used Requests and BeautifulSoup to extract information from JustWatch India.

**Movie and TV show attributes:**
- Title
- Release Year
- Genre
- IMDb Rating
- Runtime
- Age Rating
- Production Country
- Streaming Services
- JustWatch URL

### 2. Data Cleaning and Processing

- Structured scraped information into Pandas DataFrames.
- Converted release years into numeric values.
- Extracted numerical IMDb ratings.
- Filtered records based on the selected release-year period.
- Prepared movie and TV show datasets for analysis.

### 3. Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Average IMDb ratings for movies and TV shows.
- Distribution of popular genres.
- Streaming service availability.
- Differences in movie and TV show ratings.

### 4. Data Visualisation

Created visualisations using Matplotlib and WordCloud to represent:

- Top movie and TV show genres.
- Streaming platform distribution.
- Genre popularity.

## Key Findings

Based on the saved notebook outputs:

| Analysis | Result |
|---|---:|
| Average movie IMDb rating | 7.07 |
| Average TV show IMDb rating | 7.85 |
| Most frequent TV streaming platform | Netflix |
| Netflix TV show records | 15 |
| Other notable TV genres | Drama, Mystery & Thriller |

*These figures reflect the notebook's saved analysis and are not live streaming-platform statistics.*

## Dataset Export

Exported the collected and filtered datasets into CSV files for further analysis and reporting.

- Movie dataset
- TV show dataset
- Filtered movie dataset
- Filtered TV show dataset

## Skills Demonstrated

- Python Programming
- Web Scraping
- Data Extraction
- Data Cleaning
- Pandas DataFrames
- Exploratory Data Analysis
- Data Filtering
- Data Visualisation
- CSV Data Export

## Conclusion

This project provided practical experience in collecting information from web pages, processing semi-structured data, performing exploratory analysis, and presenting insights through visualisations.

It demonstrates the application of Python and data analysis techniques to transform raw web data into structured datasets and meaningful insights.
