# 🎵 Spotify Lyric Search using Machine Learning

This project implements a **text identification system** that predicts the **song title and artist** when given a **small snippet of song lyrics**.  
It uses **Natural Language Processing (NLP)** techniques and a **TF-IDF + Cosine Similarity** model.

## 📌 Project Objective
To develop a machine learning model that:
- Accepts a **lyrics snippet** as input
- Identifies the **most likely song and artist**
- Uses the **Spotify Millsong Lyrics Dataset**

This project demonstrates practical usage of **text preprocessing, feature extraction, and similarity-based ML models**.

## 🧠 Approach Used

- **Text Preprocessing**
  - Lowercasing
  - Removing punctuation
  - Stop-word removal
  - Tokenization (whitespace-based)

- **Feature Extraction**
  - TF-IDF (Term Frequency–Inverse Document Frequency)

- **Model**
  - Cosine Similarity for lyric matching

This is a **similarity-based NLP model**, not a classification model.

## 📂 Dataset
**Dataset Name:** Spotify Millsong Lyrics Dataset  
**File:** `spotify_millsongdata.csv`

### Key Columns Used:
| Column | Description |
|------|------------|
| `song` | Song title |
| `artist` | Artist name |
| `text` | Full song lyrics |

## ⚙️ Technologies Used
- Python 3.9+
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Jupyter Notebook

## Model Accuracy
79.00%


