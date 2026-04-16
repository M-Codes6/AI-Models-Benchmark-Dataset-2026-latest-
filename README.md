# 🤖 AI Models Benchmark Analysis (2026)

## 📌 Objective

Analyze AI models based on intelligence, cost, speed, and latency to understand real-world trade-offs and help users choose the best model.

---

## 📊 Dataset

* Source: Kaggle
* Rows: 188
* Features: Intelligence, Price, Speed, Latency, Context Window

---

## 🧹 Data Cleaning

* Converted text-based values to numeric
* Cleaned price column
* Handled inconsistent formats

---

## 📊 Exploratory Data Analysis (EDA)

### Key Observations:

* Most models have **moderate intelligence**
* Most models are **low-cost**
* Speed and latency vary widely
* Distributions are **right-skewed**

---

## 🔗 Relationship Analysis

* Intelligence vs Price → Slight positive trend
* Intelligence vs Speed → Weak relationship
* Intelligence vs Latency → No clear pattern

---

## 📈 Correlation Analysis

* Intelligence & Price → Moderate correlation (~0.57)
* Other features → Weak relationships

---

## 💰 Cost vs Performance

* Created: `value_score = Intelligence / Price`
* High value models are:

  * Low cost
  * Moderate intelligence

---

## 🏆 Model Comparison

* Best Value Models ≠ Most Intelligent Models
* Trade-off exists between cost and performance

---

## 💡 Key Insights

* High intelligence ≠ High value
* Features are mostly independent
* Market offers strong low-cost options

---

## 🎯 Recommendations

* Startups → Cost-efficient models
* Enterprises → High intelligence models
* Real-time apps → Fast + low latency models
* Budget users → High value_score models

---

## 🧠 Final Conclusion

There is no single best model — the best choice depends on use case and priorities.

---

## ⚙️ Tech Stack

* Python
* Pandas
* Matplotlib
* Seaborn
