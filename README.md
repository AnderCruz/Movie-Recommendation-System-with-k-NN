# Movie Recommendation System with k-NN (from Scratch)

## 📌 Project Overview

This project, developed by **Nowa Analytics**, explores the fundamentals of **Recommendation Systems** in Python.
The goal is twofold:

1. **Understand** how recommendation systems work by applying them to a real-world dataset of movie ratings.
2. **Implement** a custom version of the **k-Nearest Neighbors (k-NN)** algorithm from scratch, instead of relying only on existing libraries.

The dataset used is the popular **MovieLens dataset**, containing users, movies, and ratings. Our task is to build a system capable of generating **personalized movie recommendations** based on user similarities.



## 🎯 Objectives

* Learn the concept of **Recommendation Systems**.
* Generate recommendations using **user similarity** heuristics.
* Apply **Collaborative Filtering** techniques.
* Build recommendation models based on **items and users**.
* Implement the **k-NN algorithm from scratch**.
* Understand the **challenges and limitations** of recommendation systems.



## 📊 Dataset

We use the **MovieLens dataset**, which includes:

* **Users**: anonymous IDs representing individual viewers.
* **Movies**: titles and metadata of films.
* **Ratings**: numerical ratings (e.g., 1–5 stars) given by users to movies.

This dataset is widely used in research and industry for testing **recommender algorithms**.



## ⚙️ Methodology

### 🔹 Recommendation Strategies Covered

* **User-based Collaborative Filtering**
* **Item-based Collaborative Filtering**
* **Heuristic-based recommendations**
* **k-NN (k-Nearest Neighbors) algorithm**

### 🔹 Custom k-NN Implementation

Instead of relying on Scikit-learn, we implemented **k-NN manually** to deepen our understanding of how the algorithm works “under the hood.”



## 🔄 Project Pipeline

```mermaid
flowchart TD
    A[📥 Load MovieLens Dataset] --> B[🧹 Data Preprocessing]
    B --> C[🔍 Explore Ratings Distribution]
    C --> D1[👥 User-Based Similarity]
    C --> D2[🎞️ Item-Based Similarity]
    D1 --> E[⚡ k-NN Implementation (from scratch)]
    D2 --> E
    E --> F[🎯 Generate Recommendations]
    F --> G[📊 Evaluate Results & Challenges]
```



## 📈 Expected Results

* Generation of **personalized movie recommendations**.
* Understanding of **user-based** and **item-based** collaborative filtering.
* A **custom-built k-NN** algorithm, showcasing the fundamentals behind recommendation systems.
* Insights into the **challenges** of real-world recommender systems:

  * Data sparsity
  * Cold start problem (new users or items)
  * Scalability issues



## 👨‍💻 Authors

Project developed by **Nowa Analytics**
🚀 Data Science Consulting | Machine Learning Solutions
