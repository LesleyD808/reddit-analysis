# 🧠 Reddit Superuser & Topic Modeling Analysis

This project conducts an in-depth analysis of Reddit user behavior and topic dynamics using Python. It combines NLP, sentiment analysis, topic modeling, and network science to extract meaningful insights from social media data. Developed as part of a Web Science coursework at the University of Glasgow.

---

## 📁 Project Structure

```
reddit-analysis/
├── Reddit_Analysis.ipynb       # Jupyter notebook with all analysis steps
├── stopwordFile.txt            # Custom stopword list for topic modeling
├── screenshots/                # Saved visualizations from the notebook
├── README.md                   # Project description and insights
---

## 🔍 Overview

Using real-world Reddit data, this project addresses the following:

- What topics dominate the conversation?
- Who are the most influential users?
- How does user sentiment vary by topic?
- What does the interaction network look like?

The analysis includes sentiment detection, network-based superuser identification, and unsupervised topic modeling using LDA.

---

## 🛠️ Techniques & Tools

- **NLP**: `nltk`, `spaCy`, `TextBlob` for tokenization, stopwords, and sentiment
- **Topic Modeling**: `Gensim` LDA with `pyLDAvis` interactive visualization
- **Network Analysis**: `NetworkX` for graph construction and centrality metrics
- **Visualization**: `matplotlib`, `seaborn`, `pyLDAvis`

---

## 📊 Screenshots & Results

### 📌 User Interaction & Sentiment

| Comments & Sentiment | Daily Engagement |
|----------------------|------------------|
| ![](screenshots/CommentLengthDistribution.png) | ![](screenshots/DailyInteractionCount.png) |
| ![](screenshots/DistributionofPostSentiment.png) | ![](screenshots/ResponseTimeDistribution.png) |

---

### 🧵 Topic Modeling (LDA)

| Topics & Trends |
|-----------------|
| ![](screenshots/TopicAnalysis.png) |
| ![](screenshots/TopicsOverTime.png) |
| ![](screenshots/AverageInteractionCount.png) |

**Findings**:
- 10 major topics were identified, including *investment*, *cryptocurrency*, *crowdfunding*, and *finance*.
- Topic 7 had the highest token weight, focused on *stock and crypto markets*.
- Topics shifted in popularity over time, with peaks aligning to news cycles.

---

### 🕸️ Network & Superuser Analysis

| Network Visualization |
|------------------------|
| ![](screenshots/Top30UsersNetwork.png) |
| ![](screenshots/Top100UsersNetwork.png) |
| ![](screenshots/FullNetworkVisualization.png) |

**Insights**:
- Centrality metrics (betweenness, eigenvector) helped identify superusers.
- Superusers contributed disproportionately to total interactions.
- The network structure revealed scale-free properties with hub-like users.

---

## 📌 Summary of Key Insights

- **Sentiment** skewed positive but varied significantly across topics.
- **Superusers** (top 5%) drove over 60% of total engagement.
- **LDA Topic Modeling** revealed high interest in finance, tech, and markets.
- **Interaction patterns** showed clear temporal and topical trends.

---

## 👩‍💻 Author
Xinyu Dai

Email: xinyudai2002.career@gmail.com
