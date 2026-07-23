# 🧩 Customer Segmentation Pipeline

## DecodeLabs Data Science Internship | Python · Pandas · Scikit-learn · PCA · K-Means

*The problem:* Raw consumer behavioral data often contains high-dimensional noise and feature scale disparities, making it difficult for standard distance-based algorithms to discover meaningful customer groupings without biasing results toward high-magnitude features.  

*The solution:* An end-to-end Unsupervised Learning architecture (**Scale, Compress, Cluster, Translate**) using `StandardScaler`, Principal Component Analysis (PCA), and iterative K-Means clustering to extract actionable business personas for strategic marketing and enterprise collaborative filtering.

---

## 📌 Project Overview

This project implements an **Input-Process-Output (IPO)** unsupervised learning framework designed to uncover hidden mathematical groupings in unlabeled retail transaction data. 

By mapping high-dimensional customer signals down to localized PCA space and optimizing cluster separation via the **Elbow Method** and **Silhouette Analysis**, the pipeline translates raw behavioral features into a **Strategic Persona Matrix** to optimize marketing spend and power real-time recommendation engines.

---

## 🚀 Key Results

| Challenge | Approach | Outcome |
| :--- | :--- | :--- |
| **Spatial Proximity Distortion** | Applied `StandardScaler` to map continuous features to a common geometric range | Ensured equal mathematical voting power and normalized feature variance |
| **Curse of Dimensionality** | Reduced features via PCA retaining 95% cumulative explained variance | Eliminated spatial equidistance and improved distance metric efficacy |
| **Cluster Optimization & Translation** | Evaluated K via WCSS/Silhouette Scores and inverse-mapped PCA coordinates | Formulated 4 distinct, actionable consumer personas |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)


---

## 🔧 Pipeline Breakdown (IPO Architecture)

Raw Consumer Signals ➔ Feature Selection & Cleaning ➔ Mathematical Scaling (StandardScaler)
│
▼
Dimensionality Reduction (PCA - 95% Var)
│
▼
Iterative K-Means Clustering
(Elbow Method & Silhouette Evaluation)
│
▼
Reverse-Engineering & Inverse Transform
│
▼
Strategic Persona Matrix
(Affluent Conservatives, High-Value Trendsetters, etc.)

### 1️⃣ Mathematical Standardization (Scale)
- Continuous variables scaled using `StandardScaler` to prevent features with large magnitudes (e.g., annual income) from dominating Euclidean distance calculations.

### 2️⃣ Dimensionality Reduction (Compress)
- Applied Principal Component Analysis (PCA) to orthogonalize feature axes and project data into a lower-dimensional subspace while maintaining a **95% cumulative explained variance** threshold.

### 3️⃣ Iterative K-Means Clustering (Cluster)
- Minimized Within-Cluster Sum of Squares (WCSS / Inertia) to find cohesive clusters.
- Validated optimal $K$ using the **Elbow Method** (point of diminishing returns) and **Silhouette Scores** (cohesion vs. separation).

### 4️⃣ Reverse-Engineering & Persona Mapping (Translate)
- Inverse-transformed PCA synthetic coordinates back into human-interpretable physical dimensions.
- Mapped clusters to a **Strategic Persona Matrix**:
  - *Affluent Conservatives*
  - *High-Value Trendsetters*
  - *Budget-Conscious Explorers*
  - *Conservative Minimizers*

---

## 📊 Evaluation & Metrics Strategy

Unsupervised clustering quality was mathematically evaluated using dual metrics:
* **Elbow Method (WCSS):** Identified the exact inflection point where adding additional clusters yields marginal reduction in variance.
* **Silhouette Score:** Evaluated inter-cluster separation and intra-cluster cohesion to prevent overlapping personas.

---

## 💡 Key Learnings

- **Scale Normalization is Critical:** Distance-based models like K-Means are highly sensitive to feature scales; without `StandardScaler`, distance computations become completely skewed.
- **PCA Enhances Clustering Efficacy:** Compressing features into orthogonal axes eliminates multicollinearity and prevents high-dimensional space sparsity.
- **Translational Analytics:** Converting abstract mathematical vectors back into physical attributes is necessary to make unsupervised models actionable for business leadership and marketing teams.

---

## 👩🏾‍💻 About Me

*Adeniyi Rukayat* - Data & Operations Analyst | Abuja, Nigeria

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Fiverr](https://img.shields.io/badge/Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white)](https://fiverr.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:example@gmail.com)
[![Portfolio](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/databyrukayat)

*DecodeLabs Data Science Internship Program · 2026*
