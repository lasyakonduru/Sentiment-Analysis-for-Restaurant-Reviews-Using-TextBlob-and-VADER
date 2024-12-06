# Sentiment Analysis for Restaurant Reviews Using TextBlob and VADER 📊🍽️

---

#### **Overview 📝**

Customer feedback plays a crucial role in shaping the business strategy of service-oriented industries, especially restaurants. With traditional survey-based feedback mechanisms losing popularity, online reviews have become a powerful medium for customers to share their experiences. This project aims to implement a sentiment analysis system using two powerful algorithms—**TextBlob** and **VADER**—to analyze restaurant reviews and provide actionable insights for business improvement.

---

#### **Objective 🎯**

1. Implement sentiment analysis using **TextBlob** and **VADER**.
2. Compare the performance of the two algorithms to identify which is more effective in analyzing customer reviews.
3. Evaluate the quality of the current classification criteria and recommend the best approach for sentiment analysis.

---

#### **Dataset 📂**

The dataset contains **9,950 customer reviews** with the following variables:

- **Review**: The textual review provided by the customer.
- **Rating**: A numerical score (1-5) given by the customer.
- **Metadata**: Information about the reviewer (e.g., name, location).
- **Time**: Timestamp of the review submission.
- **Pictures**: The number of photos uploaded with the review.

---

#### **Features 🛠️**

1. **Text Preprocessing**:
   - Removal of HTML tags, numbers, special characters, and extra spaces.
   - Tokenization and lemmatization of text for better analysis.
   - Conversion of text to lowercase for uniformity.

2. **Sentiment Analysis**:
   - Implemented using **TextBlob**: A library that computes polarity and classifies sentiment as positive or negative.
   - Implemented using **VADER**: A rule-based sentiment analysis tool with a focus on context and punctuation.

3. **Performance Evaluation**:
   - Confusion Matrix
   - Accuracy
   - Precision, Recall, and F1-score for both models.
   - Comparison of TextBlob and VADER to the current threshold-based system (rating ≥3 as positive, <3 as negative).

---

#### **Results 📈**

- **VADER**:
  - **Accuracy**: 81.72%
  - **Precision**: 89% (Negative), 77% (Positive)
  - **F1-Score**: 80% (Negative), 83% (Positive)
  - **Best Performance**: VADER excels in recall for positive sentiment and overall balance between precision and recall.

- **TextBlob**:
  - **Accuracy**: 81.15%
  - **Precision**: 89% (Negative), 76% (Positive)
  - **F1-Score**: 79% (Negative), 83% (Positive)
  - **Slightly Lower Performance**: TextBlob performs well but is marginally less accurate than VADER.

---

#### **Key Findings 🔍**

- The **current rating-based classification system** (≥3 as positive, <3 as negative) is overly simplistic and misses the nuances of textual sentiment.
- **VADER** outperforms TextBlob and the current system due to its contextual understanding of text, punctuation, and intensity.
- Sentiment analysis models can significantly enhance decision-making by identifying customer pain points and areas of improvement.

---

#### **Recommendations ✅**

1. **Adopt VADER**: Use VADER for sentiment analysis due to its higher accuracy and ability to process nuanced textual reviews effectively.
2. **Enhance Customer Feedback System**: Integrate real-time monitoring of reviews to identify and address customer concerns promptly.
3. **Combine Sentiment and Ratings**: Use a hybrid approach to gain deeper insights by combining sentiment scores with ratings.

---

#### **Technologies Used 💻**

- **Python**: Programming language for data processing and modeling.
- **Pandas**: Data manipulation and analysis.
- **TextBlob**: For sentiment analysis.
- **VADER**: Rule-based sentiment analysis.
- **Matplotlib/Seaborn**: Data visualization.

---

#### **Contributors 🤝**

- **Lasya Priya Konduru**: Data Scientist & NLP Enthusiast  
- **LinkedIn:** *(https://www.linkedin.com/in/lasya-priya-k/)*

---

#### **License 📜**

This project is licensed under the [MIT License](LICENSE).

---

#### **Acknowledgments 🙏**

- **TextBlob**: For providing a simple API for sentiment analysis.
- **VADER**: For offering an excellent rule-based sentiment analyzer.
- **Matplotlib/Seaborn**: For creating beautiful visualizations.

---

🎉 **Thank you for exploring the project!** Feel free to reach out with any questions, suggestions, or feedback.
