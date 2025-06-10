# Netflix Viewing Trends

This is a data visualization project analyzing various aspects of Netflix's viewing patterns, revenue, and content distribution. The project was built entirely using Jupyter Notebooks in Visual Studio Code, powered by a Python virtual environment (`.venv`).

---
## 📁 Project Structure
![ChatGPT Image May 25, 2025, 06_43_30 PM](https://github.com/user-attachments/assets/1b4b0597-43ab-4fb9-aee1-b016bd14a666)
---


## ⚙️ How it works

1. **Data Cleaning**  
   The notebook `data_cleaning.ipynb` reads the 3 raw datasets from `data/raw/`, performs cleaning (e.g. handling missing values, renaming columns, formatting, etc.), and saves the cleaned versions into `data/processed/`.

2. **Exploratory Data Analysis (EDA)**  
   The notebook `eda_netflix.ipynb` loads the cleaned datasets and performs:
   - Summary statistics
   - Trend analysis
   - Visualizations (bar plots, line charts, etc.)
   - Identification of key patterns, outliers, and insights

3. **Environment**  
   - All notebooks were developed and run using Visual Studio Code.
   - A Python virtual environment `.venv` is used to manage dependencies.

---

## 🛠 Setup Instructions
⚠️ The .venv folder (Python virtual environment) is not included in this repository, as it's generally not pushed to GitHub for size and portability reasons.

**Step 1: Create a new virtual environment**
python -m venv .venv

**Step 2: Activate the environment**
For Windows:
.venv\Scripts\activate
For macOS/Linux:
source .venv/bin/activate

**Step 3: Install the required dependencies**
pip install -r requirements.txt

---
## 📊 Datasets Used

All datasets were sourced from Kaggle:
- **MoviesOnStreamingPlatforms_updated.csv**
- **Netflix Revenue updated.csv**
- **TV_Shows.csv**

---


---

## 📦 Datasets Used

1. **Movies on Streaming Platforms** – Contains details about various movies across platforms.
2. **Netflix Revenue Data** – Tracks quarterly revenue growth from different regions over time.

---

## 🔧 Data Cleaning (`data_cleaning.ipynb`)

Key preprocessing steps:
- Handled **missing values** and **duplicates**
- Renamed and standardized **column names**
- Unified **date and rating formats** for consistency
- Cleaned numerical and categorical data

📸 _[Screenshot of cleaned dataframe/code in presentation]_

---

## 🔍 Exploratory Data Analysis (`Final_Eda_Netflix.ipynb`)

### 1. **Revenue Trends**
- 📈 Netflix's revenue has seen **steady global growth**, especially in **North America and EMEA**.
- Revenue peak aligned with the **COVID-19 pandemic**, indicating increased digital consumption.

### 2. **Genre & Content Insights**
- 🎬 Most common genres on Netflix include **Drama**, **Comedy**, and **Documentary**.
- **Content rating** analysis shows Netflix has a large library of **PG-13** and **TV-MA** content.

### 3. **Distribution by Platform**
- Netflix leads with a large collection of content compared to other platforms like **Hulu** and **Prime Video**.

### 4. **Runtime & Year of Release**
- Runtime distributions show a focus on content under **2 hours**.
- Spike in new releases between **2010–2020**, aligning with Netflix’s global expansion.

🖼️ _[2–3 Visuals from Final_Eda_Netflix.ipynb]_

---

## 🎨 Data Visualization

We used:
- `matplotlib` and `seaborn` for static plots
- `plotly` for interactive charts
- Clear labeling and annotations for storytelling

📌 Visuals included:
- Line charts, histograms, bar plots, scatter plots, and heatmaps

---

## 📚 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `missingno`

---

## 💡 Key Insights Summary

- **Steady revenue growth** with North America being the largest contributor.
- **PG-13** and **TV-MA** dominate the content ratings.
- **Drama and Comedy** are the most preferred genres.
- Netflix has significantly **more content** than other platforms.

These insights can guide **content strategy, user segmentation, and platform investments**.

---

## 🧑‍💻 Developed By

Aditya and team 

---


## 📌 Notes

- This project is educational and aimed at showcasing skills in data wrangling, preprocessing, and visualization using Python and Jupyter Notebooks.
- The `.venv` folder is not included in GitHub and should be recreated locally via `python -m venv .venv` and installing required libraries via `pip`.

---

