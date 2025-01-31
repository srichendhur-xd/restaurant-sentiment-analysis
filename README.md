# Restaurant Reviews Sentiment Analysis

## 📌 Project Overview
This project classifies restaurant reviews as **positive** or **negative** using **Natural Language Processing (NLP)** and **Machine Learning (ML)** models. Various classifiers are compared to identify the best-performing model.

## 📂 Dataset
- **Source**: A TSV file containing restaurant reviews and sentiment labels.
- **Columns**:
  - `Review`: Textual feedback from customers.
  - `Liked`: Binary label (1 = Positive, 0 = Negative).

## 🚀 Technologies Used
- **Libraries**: Pandas, NumPy, NLTK, Scikit-learn, Matplotlib, Seaborn, XGBoost
- **ML Models**: Naive Bayes, Logistic Regression, Random Forest, SVM, XGBoost
- **Platforms**: Google Colab

## 🔍 Workflow
1. **Data Preprocessing**: Cleaning, stopword removal, stemming.
2. **Feature Extraction**: TF-IDF vectorization.
3. **Dimensionality Reduction**: PCA (2D visualization).
4. **Model Training & Evaluation**: Multiple classifiers tested for accuracy.
5. **Results Visualization**: Accuracy comparison using Seaborn.

## 📊 Model Performance
| Model            | Accuracy |
|-----------------|----------|
| GaussianNB      | 70%      |
| MultinomialNB   | 74.5%    |
| BernoulliNB     | 75.5%    |
| Logistic Reg.   | 73.5%    |
| Random Forest   | 69.5%    |
| SVM             | 75.5%    |
| XGBoost         | 68.5%    |

**Best Models:** BernoulliNB & SVM (75.5%)

## 📈 Future Scope
- Implement **deep learning** (LSTM, BERT, GPT)
- Extend to **multi-class** sentiment classification
- **Real-time** deployment for live feedback analysis
- Support **multiple languages**
- Integrate with **BI tools** (PowerBI, Tableau)

## 🛠 Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/srichendhur-xd/restaurant-sentiment-analysis
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script in Jupyter Notebook or Google Colab.

---
Made with ❤️ by **Sri Chendhur**
