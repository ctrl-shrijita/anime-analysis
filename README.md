# anime-analysis
# 🎌 Anime Popularity and Ratings Analysis

This project explores a dataset of anime shows to uncover insights related to their ratings, popularity, genres, and types. Through visualizations and basic exploratory data analysis, we aim to understand what makes certain anime more popular or highly rated than others.

---

## 📂 Dataset Description

The dataset (`anime-checkpoint.csv`) contains metadata on over 12,000 anime titles. Each entry includes:

- **`anime_id`**: Unique identifier for the anime  
- **`name`**: Title of the anime  
- **`genre`**: Comma-separated genres (e.g., Action, Comedy, Romance)  
- **`type`**: Format of the anime (TV, Movie, OVA, etc.)  
- **`episodes`**: Number of episodes (some marked as "Unknown")  
- **`rating`**: Average user rating (out of 10)  
- **`members`**: Number of users who added it to their list (proxy for popularity)

The dataset was likely sourced from MyAnimeList and is suitable for EDA and basic ML tasks.

---

## 📊 Summary of Findings

- **Most anime ratings cluster between 6.5 to 8.5**, showing generally favorable reviews.
- **TV shows** dominate the dataset, followed by Movies and OVAs.
- A **few anime have extremely high member counts**, indicating cult or mainstream popularity.
- **Action, Comedy, and Drama** are among the most frequent genres.
- There's a weak but visible **correlation between popularity (members) and ratings**.

Visualizations include:
- Rating distributions
- Popularity histograms
- Genre frequency
- Type-wise countplots
- Scatter plots showing relationships between variables

---

## ⚙️ How to Run the Notebook

1. Clone or download the repository:
   ```bash
   git clone https://github.com/yourusername/anime-analysis.git
   cd anime-analysis
