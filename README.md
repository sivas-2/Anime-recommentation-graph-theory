# 🎌 Graph-Based Anime Recommendation System

A **powerful, explainable anime recommendation system** built using **Graph Theory and Personalized PageRank**.  
The system models **users, anime, and genres as a graph** and performs **random walks** to generate personalized recommendations.

---

## 🚀 Features

- Graph-based recommender (User–Anime–Genre)
- Personalized PageRank (Random Walk with Restart)
- Anime–Anime similarity using cosine similarity
- Explainable recommendations
- Interactive graph visualizations
- Scalable & modular design

---

## 📊 Datasets

### 1️⃣ User Ratings Dataset

---

## 🧠 Methodology

### Graph Structure
- **Nodes**
  - Users
  - Anime
  - Genres

- **Edges**
  - User → Anime (rating-based)
  - Anime → Genre
  - Anime ↔ Anime (similarity-based)

### Recommendation Algorithm
- Personalized PageRank
- Strong restart bias to preserve personalization
- Weighted edges to control influence

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- NetworkX
- Scikit-learn
- PyVis
- Matplotlib

## Limitation (Due to Hardware Constraints)

Due to limited laptop memory and processing power, the recommendation system is built using a reduced dataset that includes only popular anime (based on number of ratings/members). Full-scale graph construction on the complete dataset was not feasible, as it caused memory overflow and performance issues. Therefore, recommendations are generated from a filtered subset of high-engagement anime while preserving the core graph-based methodology.
