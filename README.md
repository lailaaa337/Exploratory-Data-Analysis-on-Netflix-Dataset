#  Netflix Titles Dataset Analysis (Data Science Project)

##  Overview
This project performs an in-depth **Data Analysis on the Netflix Titles Dataset**, exploring patterns, trends, and insights from movies and TV shows available on the platform.

The analysis focuses on:
-  Data cleaning and preprocessing  
-  Exploratory Data Analysis (EDA)  
-  Statistical insights and visualization  

The dataset contains over **8,800 titles**, providing a comprehensive view of Netflix’s content library.

---

##  Features

-  Data loading and preprocessing  
-  Handling missing values and cleaning data  
-  Data transformation and feature engineering  
-  Exploratory Data Analysis (EDA)  
-  Statistical analysis (mean, median, distributions)  
-  Visualization of trends and patterns  

---

##  Dataset Overview

The dataset includes key information such as:

- `type` → Movie or TV Show  
- `title` → Name of the content  
- `cast` → Actors involved  
- `country` → Country of origin  
- `date_added` → When content was added  
- `rating` → Content rating  
- `duration` → Length (minutes/seasons)  
- `genres` → Categories  
- `description` → Summary  

> The dataset contains **8,807 entries** with diverse global content :contentReference[oaicite:0]{index=0}.

---

##  Data Cleaning & Preparation

Several preprocessing steps were applied:

- Removed unnecessary columns (`show_id`, `director`, etc.)  
- Handled missing values:
  - Filled missing `country` with `"Unknown"`  
  - Replaced missing `cast`, `rating`, and `duration`  
- Converted and split date fields  
- Renamed columns (`listed_in` → `genres`)  
- Removed duplicate entries  
- Extracted numerical values from duration  

> These steps improved data quality and usability for analysis :contentReference[oaicite:1]{index=1}.

---

##  Exploratory Data Analysis (EDA)

The project explores:

- Distribution of Movies vs TV Shows  
- Content growth over time  
- Duration patterns (minutes vs seasons)  
- Country-wise content distribution  
- Genre analysis  
- Rating distribution  

---

##  Key Insights

- Netflix offers both movies and TV shows with different duration formats  
- Content is distributed across multiple countries  
- Some metadata fields required cleaning due to missing values  
- Genre diversity plays a major role in content categorization  

> As shown in the analysis (page 2), multiple statistical metrics were computed to understand trends :contentReference[oaicite:2]{index=2}.

---

##  Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

##  Project Structure

```

project/
│── dataScience.ipynb     # Main analysis notebook
│── datasetAnalysis.pdf   # Report/documentation
│── README.md

````id="c4jrmk"



##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/netflix-analysis.git
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Open the notebook:

   ```bash
   jupyter notebook
   ```

4. Run all cells in `dataScience.ipynb`

---

##  What I Learned

* Data cleaning and preprocessing techniques
* Handling missing and inconsistent data
* Performing exploratory data analysis
* Extracting insights from real-world datasets
* Data visualization best practices

---

##  Future Improvements

* Add interactive dashboards (Power BI / Tableau)
* Perform time-series analysis
* Apply machine learning for prediction
* Analyze user preferences and trends

---

##  Notes

* Dataset sourced from Kaggle
* Some fields required preprocessing due to missing data

---

##  Author

**Laila Tarek**
**Hana Tariq**

```

