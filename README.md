# Netflix Data Analysis

Exploratory data analysis project built around the Netflix titles dataset. The project cleans the raw data, explores content trends, and presents insights through both a Python notebook and a Power BI dashboard.

## Project Overview

This analysis focuses on understanding Netflix content by looking at:

- Movies versus TV Shows distribution
- Content added over time
- Top contributing countries
- Common content ratings
- Trends by content type and year
- Most popular genres
- Cleaned dataset generation for further reporting

## Repository Contents

| File / Folder | Description |
| --- | --- |
| `NetflixDataAnalysis.ipynb` | Main Python notebook for cleaning and exploratory data analysis. |
| `netflix_titles.csv` | Raw Netflix titles dataset. |
| `cleaned_netflix.csv` | Cleaned and transformed dataset exported from the analysis workflow. |
| `Netflix_EDA_project.pbix` | Power BI dashboard/report file. |
| `Dashboard image.png` | Static dashboard preview image. |
| `Dashboard Demonstration.mp4` | Video demonstration of the dashboard. |
| `Pictures/` | Image assets used in the dashboard/report. |
| `requirements.txt` | Python dependencies required to run the notebook. |

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

## Setup

1. Clone or download this repository.
2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:

   ```bash
   jupyter notebook NetflixDataAnalysis.ipynb
   ```

## Analysis Workflow

The notebook follows these main steps:

1. Load the raw Netflix dataset.
2. Remove unnecessary unnamed columns.
3. Fill missing values in fields such as director, cast, country, and rating.
4. Convert `date_added` into a proper datetime column.
5. Create new time-based features such as month and year.
6. Split duration into numeric value and duration type.
7. Explore content distribution using visualizations.
8. Split multi-value country and genre fields for deeper analysis.
9. Export the final cleaned dataset as `cleaned_netflix.csv`.

## Dashboard

The Power BI report summarizes the cleaned Netflix data with interactive visuals. It includes insights into content type, country, genre, rating, directors, and overall catalog trends.

Preview:

![Dashboard Preview](Dashboard%20image.png)

## Output

The main processed output is:

```text
cleaned_netflix.csv
```

This file can be reused for Power BI reporting, additional Python analysis, or machine learning experiments.

