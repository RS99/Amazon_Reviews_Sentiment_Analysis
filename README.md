Amazon Reviews Sentiment Analysis

📌 Project Overview

This project performs sentiment analysis on Amazon product reviews to classify them into three categories:

Positive (2) 🟢: Ratings of 4 or 5

Neutral (1) 🟡: Rating of 3

Negative (0) 🔴: Ratings of 1 or 2

It utilizes Natural Language Processing (NLP) techniques, machine learning models, and data visualization to analyze customer feedback and understand sentiment trends over time.

📂 Dataset Description

File: amazon_reviews.csv

Columns:

reviewText: The actual review text 📝

overall: Star rating given by the customer ⭐

reviewerName: Name of the reviewer

reviewTime: Date of the review 🗓️

year: Extracted year from the review date 📆

🛠 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/amazon-reviews-sentiment-analysis.git
cd amazon-reviews-sentiment-analysis

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

jupyter notebook amazon_reviews.ipynb

🚀 Model Training & Evaluation

🔹 Preprocessing Steps

✅ Text Cleaning: Removing punctuation, converting to lowercase, and lemmatization.
✅ TF-IDF Vectorization: Transforming text into numerical features.
✅ Handling Class Imbalance: SMOTE oversampling for minority classes and undersampling for dominant classes.

🔹 Machine Learning Model

Model Used: XGBoost (eXtreme Gradient Boosting) 🌟

Accuracy Achieved: ~91-92%

🔹 Evaluation Metrics

Confusion Matrix 📊

Sentiment Distribution (Before & After Prediction)

Feature Importance Visualization 🔍

📊 Results & Visualizations

🔹 Before Prediction

Sentiment Trend Over Time 📈

Word Cloud of Most Common Words ☁️

Review Length Distribution 📊

🔹 After Prediction

Updated Sentiment Trends Over Time 📈

Most Common Words in Predicted Positive Reviews ☁️

Updated Review Length Distribution 📊

🔮 Future Improvements

🚀 Try Deep Learning Models (LSTMs, Transformers)
📊 Enhance Feature Engineering for Sentiment Context
⚡ Optimize Hyperparameters for Better Performance

📝 Contributors

👨‍💻 Rahul Sharma - GitHub Profile

⚖️ License

This project is open-source under the MIT License. Feel free to use and contribute! 🎉

