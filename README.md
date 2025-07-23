# 🧠 K-Means Text Clustering with TF-IDF | NLP Project

This project uses **Natural Language Processing (NLP)** techniques to perform **unsupervised document clustering** using the **K-Means algorithm**. It processes a collection of textual data, vectorizes it using **TF-IDF**, and then clusters the documents based on their semantic similarity.

---

## 🔍 Project Goals

- Clean and preprocess raw text data
- Convert text into numerical format using **TF-IDF Vectorization**
- Apply **K-Means Clustering** to group similar documents
- Determine **top keywords per cluster**
- Evaluate cluster quality using **Silhouette Score**
- Visualize clusters using **PCA dimensionality reduction**

---

## 📂 Dataset

The project uses a set of textual documents stored in a `.csv` file. Each document is treated as a single data point for clustering. You can replace the dataset with any textual corpus of your choice (e.g., news articles, tweets, product reviews).

---

## 🛠️ Tech Stack & Libraries

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (`KMeans`, `TfidfVectorizer`, `silhouette_score`, `PCA`)
- NLP Preprocessing (Regex, Tokenization, Stopword Removal)

---

## 🚀 How It Works

### 1. Data Preprocessing 🧹
- Convert text to lowercase
- Remove punctuation, numbers, and stopwords
- Tokenize and rejoin cleaned words

### 2. TF-IDF Vectorization ✨
- Convert text data into numerical features using **TfidfVectorizer**
- Each document becomes a vector of word importance

### 3. Clustering 🔗
- Apply **K-Means algorithm** to group documents
- Automatically assigns a cluster label to each document

### 4. Evaluation 📊
- Use **Silhouette Score** to evaluate how well the clustering has performed

### 5. Interpretation 🧾
- Extract **top N keywords** from each cluster
- Understand what each cluster is about based on its representative terms

### 6. Visualization 📈
- Reduce TF-IDF vectors to 2D using **PCA**
- Plot documents with cluster labels using a color-coded scatter plot

---

## 📷 Sample Output

- **Top Terms per Cluster**
