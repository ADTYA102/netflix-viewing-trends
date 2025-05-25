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

## ✅ Rubric Coverage

| Criteria                                    | Covered in Notebook                |
|--------------------------------------------|------------------------------------|
| Cleaning and handling missing values       | `data_cleaning.ipynb`              |
| Feature selection and engineering          | `data_cleaning.ipynb`, `eda_netflix.ipynb` |
| Ensuring data integrity and consistency    | `data_cleaning.ipynb`              |
| Summary statistics and insights            | `eda_netflix.ipynb`                |
| Identifying patterns, trends, and anomalies| `eda_netflix.ipynb`                |
| Handling outliers and data transformations | `data_cleaning.ipynb`              |
| Initial visual representation              | `eda_netflix.ipynb`                |

---

## 📌 Notes

- This project is educational and aimed at showcasing skills in data wrangling, preprocessing, and visualization using Python and Jupyter Notebooks.
- The `.venv` folder is not included in GitHub and should be recreated locally via `python -m venv .venv` and installing required libraries via `pip`.

---

