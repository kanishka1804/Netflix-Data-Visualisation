#  Netflix Dataset Analysis & Visualization

This project performs an Exploratory Data Analysis (EDA) on a Netflix dataset using Python. It explores various insights about the content available on Netflix through visualizations.

---

##  Project Objectives

- Clean and preprocess the Netflix dataset
- Analyze:
  - Distribution of Movies vs TV Shows
  - Proportion of content ratings
  - Movie duration patterns
  - Release trends over the years
  - Top contributing countries
  - Yearly comparison of Movies vs TV Shows

---

##  Dataset
The dataset (`netflix_dataset.csv`) includes the following relevant columns:
- `type`: Indicates whether the title is a Movie or TV Show
- `title`: Name of the content
- `country`: Country of origin
- `release_year`: Year the title was released
- `rating`: Content rating (e.g., TV-MA, PG, etc.)
- `duration`: Duration in minutes (for Movies) or seasons (for TV Shows)
- **File:** `netflix_dataset.csv`
- **Source:** [Kaggle - Netflix Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

##  Technologies Used

- Python
- pandas
- matplotlib

---

## Visualizations

The notebook generates the following plots:

1. **Content Type Distribution** – Bar chart showing the count of Movies vs TV Shows.
2. **Rating Distribution** – Pie chart illustrating the proportion of different content ratings.
3. **Movie Duration Distribution** – Histogram showing the distribution of movie lengths.
4. **Titles Released Per Year** – Scatter plot of number of titles released annually.
5. **Top 10 Countries** – Horizontal bar chart showing countries with the most titles.
6. **Movies vs TV Shows Over Time** – Subplot comparing yearly trends in Movies and TV Shows.


---

##  How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/netflix-eda.git
cd netflix-eda
