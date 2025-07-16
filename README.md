# Student-Performance-Prediction

This project uses demographic and background information to predict a student's average exam score across math, reading, and writing.

## 📌 Objective
To build a regression model that predicts a student's average score based on features like gender, lunch type, parental education, and test preparation.

## 📂 Dataset
- Source: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Size: 1000 rows × 8 columns

## 🧪 Features Used
Selected based on correlation with target:
- `lunch_standard`
- `test preparation course_none`
- `gender_male`
- `parental level of education_bachelor's degree`
- `race/ethnicity_group E`

**Target:** `avg_score` (mean of math, reading, and writing scores)

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots of scores
- Gender vs average score comparison using boxplots
- Feature correlation heatmap

## 🧠 Model Used
- **Random Forest Regressor**

## 📈 Performance
| Metric | Value |
|--------|-------|
| RMSE   | 14.20 |
| R²     | 0.058 |

## 📌 Key Insights
- Lunch type and test preparation course have the strongest influence on performance.
- Predicting average scores from demographics alone has limited accuracy, but gives useful patterns.

## 🛠 Future Improvements
- Add attendance, homework scores, or behavior data
- Try classification instead (e.g., grade A/B/C)

## 💡 Skills Demonstrated
- EDA with Pandas, Seaborn, Matplotlib  
- Feature selection using correlation  
- Regression modeling with Scikit-learn  
- Performance evaluation using RMSE & R²
