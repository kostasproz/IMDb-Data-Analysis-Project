# 🎬 IMDb Data Analysis Project  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)  
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)  
![Libraries](https://img.shields.io/badge/Libraries-pandas%2C%20numpy%2C%20matplotlib%2C%20seaborn%2C%20plotly-green)  

## 📌 Overview  
This project explores **IMDb’s open dataset** to uncover patterns in movie ratings, genres, and popularity.  
Using **Python** and **data science techniques**, I processed multiple `.tsv.gz` IMDb files (movies, ratings, crew, names, etc.) to build insights about the film industry.  
The project focuses on **data cleaning, exploratory analysis, feature engineering, and visualization** to answer questions such as:  
- Which genres dominate IMDb?  
- How do ratings and popularity change across years?  
- Which directors and actors consistently appear in top-rated movies?  

---

## 🛠️ Techniques & Tools  
- **Large-Scale Data Handling**: Efficiently processed multi-million row `.tsv.gz` IMDb datasets  
- **Data Wrangling & Cleaning**: pandas, NumPy (missing values, type conversions, dropping/merging columns)  
- **String Processing & Text Handling**: regex, string splitting, exploding nested lists into rows  
- **Feature Engineering**: extracting release years, genres, professions, and restructuring hierarchical data  
- **Exploratory Data Analysis (EDA)**: grouping, correlation analysis, pivot tables, descriptive stats  
- **Data Visualization**:  
  - *Matplotlib & Seaborn* → heatmaps, boxplots, distributions, scatterplots  
  - *Plotly* → interactive charts and dashboards  
- **Relational Data Merging**: combining multiple IMDb datasets (movies, ratings, crew, people)  
- **Outlier Handling & Filtering**: cleaning incomplete/extreme records to avoid bias  

---

## 📊 Key Insights  
- **Drama** is the most frequent genre, but **Documentaries** and **Animation** often achieve higher average ratings.  
- Ratings have remained relatively stable over time, while **popularity (votes)** tends to spike for more recent releases.  
- Certain directors/actors dominate **top-rated movies**, highlighting the strong impact of specific creators.  
- Genre diversity has expanded significantly in the last two decades.  

---

## 📂 Project Structure  
