# FAA Wildlife Strikes – Data Analysis

This project analyzes wildlife strike incidents involving aircraft in the United States, based on the FAA Wildlife Strike Database. The goal is to identify patterns, trends, and potential risk factors to improve aviation safety.

## Dataset
Source: [FAA Wildlife Strike Database](https://wildlife.faa.gov/)  
Dataset used in this project covers incidents up to February 2025: [Kaggle Dataset](https://www.kaggle.com/datasets/bartekmietlicki/faa-wildlife-strikes)

## Project Objectives
- Analyze historical wildlife strike incidents
- Identify seasonal and geographical patterns
- Visualize trends in frequency and severity of events
- Explore potential risk factors (species, time of day, airport location)
- Examine imbalanced target variable distributions and evaluate balancing techniques

## Tools & Libraries
- Python 3.x
- pandas, numpy
- matplotlib, seaborn, plotly
- airportsdata, timezonefinder, astral
- tqdm, gdown

## Notes
This project is provided in two formats due to technical limitations when committing Jupyter notebooks with outputs (Plotly interactive charts, widget states) from Kaggle/Colab to GitHub:
- **`Aircraft_Wildlife_Strikes.ipynb`** – clean notebook **without outputs**, preserved mainly for code reference and version control.  
- **`Aircraft Wildlife Strikes.html`** – full **report with outputs** (all visualizations and results), recommended for quick review.  

The project was originally created in the Colab environment, and using it guarantees its full functionality. Links to external notebooks:  
- [Google Colab notebook](https://colab.research.google.com/drive/1B0NamPImVrFWOxjKxfZpaaoAjG6Iz69N)  
- [Kaggle notebook](https://www.kaggle.com/code/bartekmietlicki/aircraft-wildlife-strikes)

Author: Bartosz Mietlicki
