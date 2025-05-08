# 📊 Netflix Popular Movies Analysis

This data science project explores a dataset of nearly 10,000 popular Netflix movies and shows, analyzing trends in ratings, genres, durations, and viewer engagement (votes).

## 📁 Dataset

- **File Name**: `n_movies.csv`
- **Size**: ~10,000 entries
- **Columns**:
  - `title`: Movie or show title
  - `year`: Release year
  - `certificate`: Age rating
  - `duration`: Length of the content
  - `genre`: Genre(s)
  - `rating`: IMDb rating
  - `description`: Short plot summary
  - `stars`: Lead actors
  - `votes`: Number of IMDb votes

## 🧪 Project Goals

- Clean and preprocess raw movie data
- Analyze:
  - Most common genres
  - Distribution of IMDb ratings
  - Relationship between duration and rating
  - Popular actors and frequently recurring stars
- Visualize key findings with Matplotlib and Seaborn

## 🛠️ Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Data Cleaning & Visualization

## 📈 Key Insights

- Drama and Comedy are the most common genres on Netflix
- High-rated content tends to have shorter runtimes
- TV-MA is the most frequent certificate
- Star power (popular actors) correlates with vote counts

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/netflix-movie-analysis.git
   ```
2. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Netflix_Polpular_Movies_Analysis.ipynb
   ```

## 📌 Future Work

- Build a content recommendation engine
- Analyze trends over time
- Integrate with TMDB/IMDb API for real-time updates

## 📄 License

This project is open-source and available under the MIT License.
