#  Sentiment Analysis on IMDb Movie Reviews

##  Project Overview
Analyze text data to discern sentiment, aiding businesses in 
customer feedback assessment and decision-making.
Built as part of the **Pinnacle Labs Data Science Internship 2026**.

---

##  Dataset
| Property | Details |
|---|---|
| **Name** | IMDb Movie Reviews |
| **Source** | HuggingFace Datasets |
| **Total Reviews** | 50,000 |
| **Training Set** | 25,000 reviews |
| **Testing Set** | 25,000 reviews |
| **Labels** | Positive & Negative |

---

##  Models Used
| Model | Accuracy |
|---|---|
| Naive Bayes | 86.48% |
| Logistic Regression | 89.26% ✅ Best |

---

##  Technologies Used
- Python
- Scikit-learn
- TF-IDF Vectorization (Bigrams)
- Matplotlib & Seaborn
- WordCloud
- HuggingFace Datasets
- Google Colab

---

##  Project Structure
sentiment-analysis-imdb/
│
├──  sentiment_analysis.ipynb   
└──  README.md                  

---

##  How to Run
1. Open the notebook in Google Colab
2. Run all cells top to bottom
3. Test your own reviews in the last cell!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wilsonkatam9/Sentiment-analysis-IMBD/blob/main/Sentiment_Analysis.ipynb)

---

##  Results
-  Handles negation correctly ("Not a good movie" → Negative)
-  Bigram TF-IDF for better context understanding
-  ~88-90% accuracy on 25,000 test reviews

---

##  Visualizations
- Confusion Matrix (both models)
- Model Accuracy Comparison Chart
- Word Cloud (Positive & Negative reviews)

---

##  Author
**Wilson Katam**

---

##  Internship
This project was completed as part of the
**Pinnacle Labs Data Science Internship Program 2026**
