# Fair Group Movie Recommender System

A research-oriented recommender systems project exploring collaborative filtering, group recommendation aggregation strategies, and fairness-aware recommendation techniques using the MovieLens dataset.

---

# Project Overview

This project investigates how recommender systems can generate fair and balanced recommendations for groups of users rather than only individual users.

The project implements:

- User-based collaborative filtering
- Group recommendation strategies
- Fairness-aware recommendation analysis
- Aggregation-based ranking methods
- Group satisfaction and disagreement metrics

The work is inspired by research topics in recommender systems and fair AI.

---

# Dataset

Dataset used:

- MovieLens Latest Small Dataset

Dataset statistics:

- 610 users
- 9,742 movies
- 100,836 ratings
- 98.30% sparsity

---

# Project Structure

```text
fair-group-movie-recommender/
│
├── data/
├── notebooks/
├── results/
├── figures/
├── reports/
├── src/
├── README.md
└── requirements.txt
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

# Project Workflow

## 1. Exploratory Data Analysis

- Ratings distribution analysis
- User activity analysis
- Popular movie analysis
- Sparsity analysis

---

## 2. Personal Recommendation System

Implemented:

- User-item matrix
- Cosine similarity
- User-based collaborative filtering
- Personalized movie recommendations

---

## 3. Group Recommendation System

Implemented multiple aggregation strategies:

### Average Aggregation
Recommends movies based on average group satisfaction.

### Least Misery
Minimizes dissatisfaction among group members.

### Borda Count
Ranks movies using voting-based aggregation.

---

## 4. Fairness Analysis

Implemented fairness-aware evaluation metrics:

- Group satisfaction
- User disagreement
- Fairness score

Compared fairness performance across recommendation strategies.

---

# Key Findings

- Different aggregation methods produce different fairness outcomes.
- Least Misery reduces dissatisfaction among users.
- Average aggregation balances group satisfaction effectively.
- Borda Count favors globally popular items but may increase disagreement.
- Fairness-aware recommendation analysis improves balanced group decision making.

---

# Example Recommendation Output

| Method | Example Recommendation |
|---|---|
| Average Aggregation | The Lego Movie (2014) |
| Least Misery | Heartbreak Ridge (1986) |
| Borda Count | Memento (2000) |

---

# Future Improvements

Possible future extensions:

- Matrix factorization methods
- Deep learning recommenders
- Sequential group recommendations
- Explainable AI for recommendations
- Real-time recommendation systems
- Streamlit interactive dashboard

---

# Author

Tanvir Ahmed


