
# 🎓 Student Performance Prediction

This project uses a dataset of student performance to predict overall academic achievement using a linear regression model.

---

## 📊 Model Evaluation & Insights

### 🎯 Objective  
This project aims to predict students' **average academic performance** based on demographic and support-related features, such as:

- **Gender**
- **Lunch type** (used as a socioeconomic proxy)
- **Test preparation course completion**

### 🧪 Model Metrics  
Using **Linear Regression**, the model yielded the following evaluation metrics:

- **Mean Absolute Error (MAE):** `11.09`
- **R-squared (R²):** `0.074`

These results indicate that the model’s predictions deviate from actual average scores by approximately 11 points, and it explains only about **7.4% of the variance** in student performance.

### 📈 Correlation Analysis  
A correlation heatmap was used to explore relationships between variables:

- **Subject scores** (math, reading, writing) showed strong mutual correlations (0.80–0.95), which is expected.
- **Test preparation course completion** had a weak-to-moderate positive correlation with scores (up to ~0.31).
- **Lunch type** showed a similar moderate effect (~0.35).
- **Gender** had a slight negative correlation with reading and writing scores (~ -0.24 to -0.30).

### 💡 Insights

- 📚 **Test preparation** seems to positively impact scores, but the effect is limited.
- 🍱 **Lunch type** (as a socioeconomic indicator) also correlates modestly with performance.
- 🚻 **Gender** appears to have a smaller effect, especially in reading and writing.
- 📉 **Overall**, the model’s low R² suggests that background features **alone** are not strong predictors of student performance.
- For stronger prediction models, including **past academic results**, **attendance records**, or **engagement metrics** could significantly improve performance.

---
