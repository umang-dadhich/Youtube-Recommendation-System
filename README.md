# Youtube-Recommendation-System-
A Machine Learning-based recommendation engine that mimics YouTube’s video recommendation algorithm. This project analyzes video metadata (title, tags, views, likes, categories, etc.) from the Kaggle YouTube dataset (INvideos.csv) to suggest relevant videos using content-based filtering, NLP, and similarity models.

# 🎬 YouTube Recommendation System | Python + Machine Learning

This project is a simplified version of YouTube's recommendation engine built using Python and machine learning techniques. It analyzes metadata such as video titles, tags, and categories from trending YouTube videos in India to suggest similar videos.

📁 **Notebook**: [`youtubeIndia.ipynb`](./youtubeIndia.ipynb)  
📊 **Dataset**: `INvideos.csv` from the [Kaggle YouTube Trending Dataset](https://www.kaggle.com/datasets)  

---

## 🔍 What It Does

This recommendation system uses **Natural Language Processing (NLP)** and **Content-Based Filtering** to:
- Understand video metadata (titles, tags, category)
- Clean and vectorize the data using **TF-IDF**
- Find similar videos using **Cosine Similarity**
- Recommend top N related videos

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**
   - Load and clean data
   - Remove duplicates and nulls
   - Merge and format relevant columns like title, tags, and description

2. **NLP + Feature Engineering**
   - Use TF-IDF Vectorizer to convert text data into numerical form
   - Combine title, tags, and description for better context

3. **Recommendation Logic**
   - Use **Cosine Similarity** on TF-IDF matrix
   - Recommend top similar videos for a given video title

4. **Evaluation & Testing**
   - Test results using user-inputted video titles
   - Return top N similar recommendations

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn)
- **NLP** (TF-IDF, Stopwords, Regex)
- **Machine Learning** (Cosine Similarity)
- **Visualization** (Matplotlib, Seaborn)
- **Jupyter Notebook**

---

## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/youtube-recommendation-system.git
   cd youtube-recommendation-system
