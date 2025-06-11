# Netflix Viewing Trends

This is a data visualization project analyzing various aspects of Netflix's viewing patterns, revenue, and content distribution. The project was built entirely using Jupyter Notebooks in Visual Studio Code, powered by a Python virtual environment (`.venv`).

---
## 📁 Project Structure
![WhatsApp Image 2025-06-11 at 18 54 15_7891be5e](https://github.com/user-attachments/assets/d8cdd1ee-fdc8-4b7b-b538-1f68624c0a01)

---


## ⚙️ How it works

1. **Data Cleaning**  
   The notebook `data_cleaning.ipynb` reads the 3 raw datasets from `data/raw/`, performs cleaning (e.g. handling missing values, renaming columns, formatting, etc.), and saves the cleaned versions into `data/processed/`.

2. **Exploratory Data Analysis (EDA)**  
   The notebook `Final_Eda_Netflix.ipynb` loads the cleaned datasets and performs:
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

![image](https://github.com/user-attachments/assets/710f2ddb-04a1-4c0c-bfd7-99e4711e52b0)


---

# 🔍 Exploratory Data Analysis (`Final_Eda_Netflix.ipynb`)

## 1. **Movies Analysis**

### 1. Content Distribution Across Streaming Platforms 

This bar chart highlights the distribution of movies across four major streaming platforms.

Prime Video dominates the content library with 73.8% of the total movies, showcasing its vast collection.

Netflix follows with 21.3%, while Hulu and Disney+ contribute significantly less at 5.4% and 3.4%, respectively.
🔍 Insight: Prime Video is clearly leading in terms of quantity, possibly indicating a focus on extensive content acquisition.

![image](https://github.com/user-attachments/assets/21cf7e16-d543-495c-ae67-2798390d3e6e)


---

### 2. Movie Ratings Distribution on IMDb 

This histogram shows the spread of IMDb ratings for the movies.

The majority of the movies have ratings clustered between 5 and 7, peaking around 6–6.5.

Very few movies have ratings below 3 or above 9.
🔍 Insight: Most movies receive average to above-average ratings, suggesting a normal distribution in perceived quality.

![image](https://github.com/user-attachments/assets/540026ba-e6ba-4e3d-9499-ae7a3806d289)


---

### 3. Movie Releases by Year (1900–2023) 

This line plot depicts how the number of movie releases has evolved over time.

There's a steady rise post-1980, with a sharp spike around 2010–2019.

A noticeable drop is observed after 2020, likely due to the impact of the COVID-19 pandemic.
🔍 Insight: The film industry saw exponential growth in the last two decades, but recent global events temporarily disrupted production.

![image](https://github.com/user-attachments/assets/1f754657-1c04-45ac-9a64-e150d7e074db)


---

### 4. Top 10 Most Common Movie Genres 

This bar chart ranks the ten most frequent genres in the dataset.

Drama is the most prevalent genre, making up 44.8% of the movies, followed by Comedy (27.7%) and Thriller (20%).

Other notable genres include Action, Horror, and Crime.
🔍 Insight: Drama and Comedy dominate storytelling, possibly because they appeal to broad audience segments.

![image](https://github.com/user-attachments/assets/5f9edaf5-26b3-4a26-98de-df2e9bcd15b9)


## **TV Shows Analysis**

### 1. TV Shows Distribution Across Streaming Platforms 

This bar chart displays the distribution of TV shows available across four major streaming platforms:

Prime Video leads with 38.2% of the shows.

Netflix follows with 34.4%, and Hulu is close behind at 31.3%.

Disney+ lags significantly with only 3.2% of the content.
🔍 Insight: TV show content is more evenly distributed across platforms compared to movies.

![image](https://github.com/user-attachments/assets/4ec514d8-d781-4e8b-b60f-afece0de2ab0)


---

### 2. TV Show Ratings Distribution on IMDb 

This histogram illustrates the IMDb ratings of TV shows on a scale of 0–10.

The majority of shows cluster around the 6 to 7.5 rating range, peaking at around 7.

Very few shows fall on the extreme ends (either below 4 or above 9).
🔍 Insight: Most TV shows receive moderately positive ratings, with a few exceptional outliers.

![image](https://github.com/user-attachments/assets/1b7f3ab8-8ccf-4ec1-8d6a-ae6d64ab6658)


---

### 3. Age Rating Distribution of TV Shows 

This bar chart categorizes TV shows based on their age ratings:

A dominant 61.7% of shows are rated 16+, suggesting more mature content.

7+ (15.1%), 18+ (13.4%), and All Ages (9.7%) follow.

Only 0.1% are rated 13+, possibly due to inconsistent labeling.
🔍 Insight: Most shows are targeted at older teens and adults, reflecting viewer demand for mature themes.

![image](https://github.com/user-attachments/assets/c1200275-4599-4ee3-a55e-b2e5972a3f85)


---

### 4. Top 10 Highest-Rated TV Shows 

This bar chart presents the top 10 highest-rated TV shows on IMDb:

"Destiny" holds the highest rating at 9.6.

Shows like "Breaking Bad", "Hunter x Hunter", and "Magical Henry" follow closely at 9.5.

All shows in the top 10 have ratings above 9.3, indicating exceptional viewer acclaim.
🔍 Insight: These elite shows stand out for their storytelling, production, and audience reception.

![image](https://github.com/user-attachments/assets/60f5069e-d920-4fdc-ad1e-3367da45702c)


## **Revenue Analysis**

### 1. Global Quarterly Revenue Trend 

This line chart shows steady revenue growth from 2019 to 2023:

Revenue increased from around $4.5 billion in 2019 to over $8 billion by 2023.

There’s a noticeable rise until late 2022, with a slight dip and rebound in early 2023.

![image](https://github.com/user-attachments/assets/34e93409-df7b-41d5-ba8a-b7e7ac441f84)


---

### 2. Regional Revenue Distribution 

This donut chart illustrates the latest quarter's revenue contribution by region:

United States & Canada: Dominates with 44% of total revenue.

Europe, Middle East & Africa (EMEA): Contributes 31%.

Latin America: 13.2%

Asia Pacific: 11.5%

![image](https://github.com/user-attachments/assets/eb3cf265-10ae-4425-bad0-2826e99121d7)


---

### 3. Global Subscriber Growth 

This line graph tracks global subscribers over time:

From 150 million in 2019 to nearly 230 million in 2023.

The steepest growth occurred between 2019 and 2021, followed by a more gradual rise.

![image](https://github.com/user-attachments/assets/7eb85ec8-16a3-4db0-b066-1885656b7cf9)


---

### 4. Average Revenue Per User by Region 

This bar chart compares average revenue per user (ARPU) by region:

United States & Canada leads with $16.18/user.

Followed by:

EMEA: $10.89

Latin America: $8.60

Asia Pacific: $8.03


This highlights a strong revenue premium in the North American market.

![image](https://github.com/user-attachments/assets/6252f726-42ae-48ff-803b-11bd96a161f0)

---


## 💡 Key Insights Summary

### 📈 1. Revenue Growth Over Time
Netflix’s annual revenue has shown consistent growth from 2002 to 2022, with a sharp incline starting around 2015.

This reflects its global expansion strategy, increased original content production, and aggressive investments in digital streaming.

### 🎬 2. Dominance of Certain Genres
The most frequently occurring genres in Netflix's catalog are Drama, Comedy, and Action, with Drama being the dominant genre.

Genre distribution shows that users are most engaged with emotionally and story-driven content.

### ⭐ 3. IMDb Rating Distribution
The majority of Netflix content is rated between 6 and 8 on IMDb.

This indicates a generally moderate to good reception among viewers, with very few extremely low-rated shows.

### 📊 4. Ratings vs Runtime & Release Year
Scatter plots reveal that longer runtime does not necessarily guarantee a higher rating.

Older shows tend to have more varied ratings, while newer content clusters more tightly in the 6.5–8 range, indicating consistent quality in recent releases.

### 🗓️ 5. Content Release Over the Years
There's a clear spike in the number of shows released after 2015, aligning with Netflix’s push for original content and market dominance.

The peak years indicate strategic content rollouts for subscriber retention.

### 🌍 6. Country-wise Content Distribution
The USA leads by a large margin in terms of the number of shows available, followed by countries like India, UK, and Canada.

This hints at Netflix’s prioritization of content production and licensing in key markets.

### 🎭 7. Genre vs Ratings
Certain genres like Documentaries and Biographies tend to have higher average IMDb ratings, suggesting niche audiences appreciate high-quality informative content.

### 📱 8. User Preferences
Users tend to prefer mid-length content (60–120 mins), making it a sweet spot for engagement.

Series and shows with ongoing sequels tend to maintain user interest longer than standalone content.


---

## 🧑‍💻 Developed By

Aditya and team 

---


## 📌 Notes

- This project is educational and aimed at showcasing skills in data wrangling, preprocessing, and visualization using Python and Jupyter Notebooks.
- The `.venv` folder is not included in GitHub and should be recreated locally via `python -m venv .venv` and installing required libraries via `pip`.

---

