
# 📊 Sentiment Analysis on GLO Telecommunication Feedback

This project conducts a comprehensive **sentiment analysis** on public complaints and customer feedback collected from GLO Nigeria subscribers. Using machine learning and NLP techniques, the project classifies user comments into **Positive**, **Neutral**, or **Negative** sentiments, across four key service categories:

* **Customer Service**
* **Data Plan**
* **Quality of Service (QoS)**
* **Tariff Plan**

---

## 🧠 Project Objective

To gain deep insight into the perception of GLO services by analyzing textual customer comments, and generate data-driven recommendations for enhancing customer satisfaction.

---

## 📁 Project Structure

```
Sentiment-Analysis/
│
├── Sentiment_Analysis_Glo.ipynb             # Main notebook with analysis and visualizations
├── Sentiment_Machine_Learning_Approach.ipynb# Alternate ML model implementations
├── Sentiment_Model.ipynb                    # Model tuning and versioning
│
├── Glo_customer_services_comment.csv        # Customer service comments
├── Glo_data_plan_comment.csv                # Data plan feedback
├── Glo_qos_comment.csv                      # Comments on quality of service
├── Glo_tariff_plan_comment.csv              # Tariff plan complaints
│
├── README.md                                # Documentation
```

---

## 📊 Sentiment Distribution Results (by Category)

### 🧑‍💼 Customer Service

* **Negative:** 152 (70.3%)
* **Positive:** 48 (22.2%)
* **Neutral:** 16 (7.4%)

> 📌 Majority of feedback highlights **poor responsiveness**, **rude agents**, and **unresolved complaints**.

---

### 📶 Data Plan

* **Negative:** 159 (72.9%)
* **Positive:** 45 (20.6%)
* **Neutral:** 14 (6.4%)

> 📌 Key concerns include **fast data depletion**, **expensive bundles**, and **poor value for money**.

---

### 📡 Quality of Service (QoS)

* **Negative:** 160 (72.7%)
* **Positive:** 43 (19.5%)
* **Neutral:** 17 (7.7%)

> 📌 Users frequently complain about **slow internet**, **frequent call drops**, and **network instability**.

---

### 💰 Tariff Plan

* **Negative:** 166 (76.1%)
* **Positive:** 38 (17.4%)
* **Neutral:** 14 (6.4%)

> 📌 Users expressed dissatisfaction with **unfavorable call rates**, **billing errors**, and **lack of transparency**.

---

## 🔧 Tools & Technologies Used

* **Python**
* **Pandas, NumPy** – data cleaning and structuring
* **Scikit-learn** – model training (Logistic Regression, Naive Bayes)
* **NLTK** – text processing
* **TF-IDF** – feature vectorization
* **Matplotlib / Seaborn** – data visualization
* **WordCloud** – visual sentiment keywords

---

## 🧪 Workflow Summary

### 1. Data Preprocessing

* Cleaned and normalized text
* Tokenization, stopword removal, lemmatization
* Labeled datasets (positive, neutral, negative)

### 2. Vectorization

* TF-IDF applied to transform text into features

### 3. Model Building

* Logistic Regression & Naive Bayes used for classification
* Model tested on all 4 categories independently

### 4. Evaluation

* Accuracy, Precision, Recall, F1-score
* Confusion matrix and sentiment distribution visualized

---

## 📈 Insights & Recommendations

* Sentiments are **heavily skewed toward negative** across all categories.
* GLO’s **customer experience strategy needs revamping**, especially around:

  * Agent support training
  * Transparent billing
  * Better internet service coverage

> 🎯 **Targeted service improvements** can reduce churn and improve brand perception.

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Percy-O/Sentiment-Analysis.git
   cd Sentiment-Analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the main notebook:

   ```bash
   jupyter notebook Sentiment_Analysis_Glo.ipynb
   ```

4. Step through the cells to view preprocessing, analysis, and final results.

---

## 📦 Requirements

You can create a `requirements.txt` like:

```
pandas
numpy
scikit-learn
matplotlib
seaborn
wordcloud
nltk
```

---

## 📬 Contact

**Author:** Percy Owoeye
**GitHub:** [@Percy-O](https://github.com/Percy-O)
**Email:** [owoeyepercyolawale@gmail.com](mailto:owoeyepercyolawale@gmail.com)

