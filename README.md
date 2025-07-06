
# 🌐 Spectral Clustering: Finding Communities in Graphs

## ✨ Overview

Welcome to this repository, which combines **rigorous theory**, **intuitive explanations**, and **practical code** to master **Spectral Clustering** for community detection in graphs.

📦 **This repository includes:**

1. 📄 **Article PDF** – The original research paper.
2. 🎓 **Presentation PDF** – Simplified and structured explanation slides.
3. 💻 **Example Code** – Jupyter notebooks applying spectral clustering to real datasets.

---

## 📝 Contents

### 📄 1. Article

- **File:** `Article.pdf`
- **Title:** *A Spectral Clustering Approach To Finding Communities in Graphs* by Scott White & Padhraic Smyth.
- **Summary:**  
  Introduces two spectral clustering algorithms (**Spectral-1** and **Spectral-2**) that maximize the **modularity function Q**, enabling efficient community detection in large and complex graphs. Demonstrated on datasets such as WordNet, NCAA football teams, and NIPS co-authorship networks.

---

### 🎓 2. Presentation

- **File:** `Presentation.pdf`
- **Description:**  
  A clear and structured presentation covering:
  - ✅ Fundamental concepts (eigenvectors, modularity Q, spectral methods)
  - ⚙️ Detailed algorithms: Spectral-1 and Spectral-2
  - 📝 Step-by-step practical examples
  - ⏱️ Complexity analysis and real-world use cases

Ideal for quick learning, technical interviews, and academic presentations.

---

### 💻 3. Example Code

#### 🐬 Dolphins Dataset

- **Notebook:** `notebook_spectral_clustering_1.ipynb`
- **Description:**  
  - Detects communities within the dolphin social network.
  - Implements spectral clustering from scratch with detailed eigen decomposition.
- **Data:** `data.zip`

<div align="center">

![Dolphins Unclustered](https://github.com/akjayant/Spectral-Clustering/blob/master/dolphins.png)
![Dolphins Clustered](https://github.com/akjayant/Spectral-Clustering/blob/master/dolphins_unclustered.png)

</div>

---

#### ⚽️ Barca vs Real Madrid

- **Notebook:** `Barca_madrid.ipynb`
- **Description:**  
  - Clusters players into their respective teams based on interaction graphs.
  - Complete pipeline: eigen decomposition, feature projection, and k-means clustering.
- **Data:** `lclassico.gml`

<div align="center">

![Barca Madrid Unclustered](https://github.com/akjayant/Spectral-Clustering/blob/master/barca_madrid.png)
![Barca Madrid Clustered](https://github.com/akjayant/Spectral-Clustering/blob/master/barca_madrid_clustered.png)

</div>

---

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/Spectral_Clustering_Approach_To_Finding_Communities_in_Graphs.git
cd Spectral_Clustering_Approach_To_Finding_Communities_in_Graphs
```

2. **Install dependencies:**

```bash
pip install numpy scipy networkx matplotlib scikit-learn
```

3. **Run the notebooks:**

Launch Jupyter Lab or Notebook and explore each notebook to understand the implementations and reproduce results.

---

## 👨‍💻 Author

- **Name:** [Your Name Here]
- **Email:** [your.email@example.com]
- **LinkedIn:** [Your LinkedIn Profile]

---

## 🔗 References

- White, S. & Smyth, P. (2004). *A Spectral Clustering Approach To Finding Communities in Graphs*. SIAM International Conference on Data Mining.
- Newman, M. (2004). Fast algorithm for detecting community structure in networks.
- Elkan, C. (2003). Using the triangle inequality to accelerate k-Means.

---

## 💡 Why This Repository?

⭐ **Master spectral clustering deeply**  
📊 **Apply concepts through practical, real-world examples**  
⚡ **Combine theoretical rigor, intuitive visualization, and implementation**

> “Divide each difficulty into as many parts as is feasible and necessary to resolve it.” – *René Descartes*

---
