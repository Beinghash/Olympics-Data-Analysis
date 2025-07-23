# 🏅 Olympics Data Analysis (1976–2008)

This project focuses on analyzing historical Olympic medal data from the Summer Games between **1976 (Montreal)** and **2008 (Beijing)**. The analysis includes insights into top-performing countries, athletes, gender participation, and trends across years. A machine learning model is also developed to predict the type of medal won (Gold, Silver, Bronze) based on athlete and event features.
This project is part of our ongoing 'Data Analysis Series' aimed at practicing real-world EDA and machine learning workflows on diverse datasets.

---

## 📂 Dataset Information

- **Source**: Summer Olympic Medals Dataset (1976–2008)
- **Total Entries**: ~15,000
- **Columns Used**:
  - `City`, `Year`, `Sport`, `Discipline`, `Event`
  - `Athlete`, `Gender`, `Country_Code`, `Country`
  - `Event_gender`, `Medal`

---

## 🎯 Objectives

1. Clean and prepare the dataset for analysis.
2. Perform Exploratory Data Analysis (EDA) to extract insights.
3. Visualize key trends across sports, countries, and gender.
4. Build a machine learning model to predict medal types.

---

## 📊 Exploratory Data Analysis Highlights

- **Top Performing Countries**: Identified countries with the most medal wins.
- **Top Athletes**: Recognized the most decorated Olympians.
- **Gender Participation**: Explored male vs female representation in sports.
- **Medal Trends Over the Years**: Visualized changes in medal counts by year.
- **Medals by Sport**: Analyzed which sports award the most medals.

---

## 🤖 Machine Learning Model

### Goal:
Predict the type of medal (Gold, Silver, Bronze) using a multi-class classification approach.

### Features Used:
- `Country`, `Sport`, `Discipline`, `Gender`, `Event_gender`, `Year`

### Model:
- **Random Forest Classifier**

### Performance:
- **Accuracy**: ~70%
- **Precision/Recall/F1-Score**: Balanced across all medal categories
- **Confusion Matrix**: Shows strong classification ability with some overlap between similar medals

---

## ✅ Conclusion

This project successfully achieved its objectives:
- Extracted meaningful insights from Olympic data
- Visualized medal trends across different dimensions
- Built a model capable of predicting medal types with ~70% accuracy

Future improvements could include additional features like athlete age, previous records, or event-specific stats to boost model performance.

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📁 Project Files

- `Olympics_Data_Analysis.ipynb` – Complete notebook with code, visuals, and ML model
- `Summer-Olympic-medals.csv` – Raw dataset
- `README.md` – Project documentation


---

## 🙋‍♂️ Author

Made by Hashir khan   
Feel free to ⭐ the repo if you found it helpful!
