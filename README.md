# 🎬 Movie Recommender System (Collaborative Filtering)

This project implements a basic movie recommendation system using collaborative filtering based on user ratings. It uses the **MovieLens dataset** and finds similar movies based on user rating correlation.


---

## 📊 Features

- Calculate average ratings and number of ratings for each movie.
- Visualize rating distributions using matplotlib and seaborn.
- Create a user-movie ratings matrix (pivot table).
- Use Pearson correlation to find similar movies.
- Filter recommendations based on the number of ratings to ensure reliability.

---

## 🧪 How It Works

1. Load rating and movie title data.
2. Merge datasets using `item_id`.
3. Create a pivot table where:
   - Rows = users
   - Columns = movie titles
   - Values = ratings
4. Choose a target movie (e.g., *Star Wars (1977)* or *Liar Liar (1997)*).
5. Calculate correlation between the target movie's ratings and all other movies.
6. Filter movies with more than 100 ratings to avoid statistical noise.

---

## 📈 Visualizations

- Histogram of number of ratings
- Histogram of average ratings
- Jointplot showing the relationship between number of ratings and average rating

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`


---

