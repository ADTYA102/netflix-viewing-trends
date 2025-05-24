# Netflix Viewing Trends

This is a data visualization project analyzing various aspects of Netflix's viewing patterns, revenue, and content distribution. The project was built entirely using Jupyter Notebooks in Visual Studio Code, powered by a Python virtual environment (`.venv`).

---

## 📁 Project Structure

netflix-viewing-trends/
│
├── data/
│ ├── raw/ # Raw datasets downloaded from Kaggle
│ │ ├── MoviesOnStreamingPlatforms_updated.csv
│ │ ├── Netflix Revenue updated.csv
│ │ └── TV_Shows.csv
│ └── processed/ # Cleaned datasets saved after preprocessing
│ ├── MoviesOnStreamingPlatforms_cleaned.csv
│ ├── Netflix Revenue updated_cleaned.csv
│ └── TV_Shows_cleaned.csv
│
├── notebooks/
│ ├── data_cleaning.ipynb # Handles all data cleaning and preprocessing
│ └── eda_netflix.ipynb # Exploratory Data Analysis and visualization
│
├── .venv/ # Python virtual environment for package management
└── README.md


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

## ✨ Author

Aditya  
Final Year B.Tech Student  
Data Visualization Mini-Project (2025)
