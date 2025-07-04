# 🎓 Student Performance Regression

This project uses linear regression to predict students' **math scores** based on features like reading & writing scores, gender, lunch type, and more. It's a full pipeline from data cleaning to model evaluation.

---

## 📌 Project Summary

- ✅ Performed EDA (Exploratory Data Analysis)
- ✅ Visualized feature relationships using histograms, heatmaps, and pairplots
- ✅ Handled categorical features using one-hot encoding
- ✅ Built and trained a Linear Regression model using Scikit-Learn
- ✅ Evaluated model performance using MSE and R² score

---

## 📂 Dataset

- **Name:** Students Performance in Exams
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Size:** 1000 rows × 8 columns

---

## 📊 Features Used

- `reading_score`
- `writing_score`
- `gender` *(encoded)*
- `lunch` *(encoded)*
- `test preparation course` *(encoded)*  
- *(Target: `math_score`)*

---

## 🧠 Model Used

- **Linear Regression** (from `sklearn.linear_model`)

---

## 📈 Results

- **R² Score:** `~0.88`
- **Mean Squared Error:** `~29.09`
- **Top Influencers:** Reading and writing scores showed the strongest correlation with math score.

---

## 🖼️ Visualizations

- Histogram of all three scores
- Heatmap to examine feature correlations
- Pairplot showing relationships among numeric features

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-Learn

---

## 🚀 Future Improvements

- Try polynomial regression
- Add cross-validation
- Experiment with other algorithms like Random Forest or XGBoost
- Deploy using Streamlit

---

## 🤘 Author

Made with ☕ and a lot of curiosity by [@shubham04-oss](https://github.com/s\Shubham04-oss)

