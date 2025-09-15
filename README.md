# 🎬 Netflix Recommendation System  

A **content-based recommendation engine** that suggests Movies & TV Shows from the Netflix catalog using **TF-IDF vectorization** and **Cosine Similarity**.  

---

## ✨ Features  
✅ Clean & preprocess Netflix dataset  
✅ Build **TF-IDF feature vectors** from textual metadata  
✅ Compute **cosine similarity matrix** for all titles  
✅ Store processed matrices & vectorizer for reuse  
✅ Recommend **Movies** & **TV Shows** separately  
✅ Simple, modular class-based design  

---

## 📂 Project Structure  
```bash
📦 netflix-recommendation
├── netflix_data.csv              # Input dataset
├── movie_data.csv                # Final cleaned dataset (title + type)
├── tfidf_matrix.npy              # Saved TF-IDF matrix
├── cosine_sim_matrix.npy         # Saved cosine similarity matrix
├── tfidf_vectorizer.pkl          # Saved TF-IDF vectorizer
├── recommendation.py             # Main script with model + class definitions
└── README.md                     # Documentation
