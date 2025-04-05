# Scoutify 🏀

**Scoutify** is a smart web platform designed to connect football stakeholders — players, clubs, agents, coaches, photographers, sponsors, and equipment suppliers — through intelligent and fair matching based on performance and preferences.

---

## 🧠 Core Intelligence (No Supervised Training)
Scoutify relies on **unsupervised methods and similarity-based matching**, without requiring pre-trained machine learning models.

### ✅ Algorithms used:

| Technique              | Used for                        | Type               |
|------------------------|----------------------------------|--------------------|
| Cosine Similarity      | Recommending agents, clubs...    | Similarity-based   |
| K-Nearest Neighbors (KNN) | Matching players to clubs, etc. | Non-supervised ML  |

> 🌟 **Cosine similarity** is used to recommend top profiles that are most similar to a club or player.  
> 🤖 **KNN** is used to match a target profile (e.g., ideal player) to the most similar real candidates.

---

## 💼 Use Cases in Scoutify

| Use Case                        | Description |
|----------------------------------|-------------|
| 🧹 Player → Club Recommendation | Find the best clubs for a player based on style, performance and budget. |
| 🧠 Club → Agent/Coach Matching | Help clubs find suitable representatives based on their needs (youth, reputation, salary, etc.). |
| 🖼 Club → Photographer           | Recommend photographers based on style and experience. |
| 💰 Club → Sponsor               | Match clubs to potential sponsors based on budget and visibility. |
| 👟 Club → Equipment Supplier    | Recommend equipment brands based on age profile and quality level. |

---

## 🌐 Technical Stack

| Component        | Technology     |
|------------------|----------------|
| Backend          | Flask (Python) |
| IA Matching      | Scikit-learn   |
| Frontend         | HTML/CSS + Jinja Templates |
| Data Processing  | pandas / NumPy |
| Deployment       | GitHub (and optional: Render, Heroku...) |

---

## 🧑‍🏫 Academic Context

This project was built as part of the **Data Science curriculum** at *Esprit School of Engineering*. It reflects our understanding of:

- 🔎 Data exploration and preprocessing  
- 🧠 Machine learning (KNN, Similarity-based AI)  
- 🧹 Real-world recommendation and matching systems  

---

## 🎓 Evaluation Requirements (as per instructor)

- ✅ Project hosted on GitHub with structured README and topics
- ✅ Post published on LinkedIn presenting the project in English
- ✅ Clear code and visualization in notebook or web app

---

🚀 Want to test the matching engine? Run it in Google Colab or host Scoutify online using Flask + Python!

