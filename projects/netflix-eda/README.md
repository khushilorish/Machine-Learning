🎬 Netflix Data Analysis (EDA)

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover trends, patterns, and business insights related to content distribution, growth, and audience targeting.

---

🎯 Objective

- Understand the distribution of Movies vs TV Shows
- Analyze year-wise growth of Netflix content
- Identify top contributing countries
- Examine audience targeting using content ratings
- Explore duration patterns for Movies and TV Shows

---

📂 Dataset

- Source: Kaggle (Netflix Movies and TV Shows dataset)
- Format: CSV
- Features include:
  "title, type, director, cast, country, date_added, release_year, rating, duration, listed_in, description"

---

🧹 Data Preprocessing

- Handled missing values in "director", "cast", and "country"
- Converted "date_added" to datetime format
- Extracted "year_added" for trend analysis
- Cleaned "duration" column by separating numeric values and units

---

📊 Exploratory Data Analysis

🔹 Content Distribution

- Movies dominate the dataset compared to TV Shows

🔹 Year-wise Growth

- Significant increase in content after 2016
- Peak around 2019–2020, followed by slight decline

🔹 Content Strategy Shift

- Gradual increase in the proportion of TV Shows in recent years
- Indicates a shift toward episodic content for better user engagement

🔹 Country-wise Analysis

- United States produces the highest amount of content
- Increasing contributions from countries like India, UK, and South Korea

🔹 Rating Analysis

- TV-MA is the most common rating
- Indicates a focus on mature audience content

🔹 Duration Analysis

- Movies: Average duration ~100 minutes
- TV Shows: Typically 1–2 seasons

🔹 Genre Insights

- Drama and International content are the most common genres
- Reflects Netflix’s focus on diverse and global storytelling

---

🔍 Key Insights

- Netflix is primarily movie-heavy but gradually shifting toward TV Shows
- Rapid content growth aligns with global expansion after 2016
- Platform is expanding internationally but remains US-dominated
- Strong focus on mature (adult) audience content
- Increasing emphasis on long-form, binge-worthy content

---

⚠️ Limitations

- No user interaction data (ratings, watch history)
- Cannot perform personalized recommendations
- Analysis limited to available metadata

---

🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

🚀 Future Work

- Build a Recommendation System using content-based filtering
- Create interactive dashboards (Power BI / Tableau)
- Extend analysis using SQL

---

📌 Conclusion

Netflix has evolved from a movie-focused platform to a globally diversified streaming service, increasingly emphasizing TV Shows, mature content, and international expansion to improve user engagement and retention.