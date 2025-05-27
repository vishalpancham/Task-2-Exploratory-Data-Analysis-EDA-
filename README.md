# Titanic Dataset - Exploratory Data Analysis (EDA)

## 🔍 Objective:
To explore the Titanic dataset using visualizations and basic statistics to understand survival patterns.

---

## 📈 Summary Statistics

- Dataset contains 891 entries and 12 columns.
- Key features include: Age, Fare, Pclass, Sex, Embarked, Survived.

---

## 🔎 Key Findings:

### 1. Survival Rate by Passenger Class

- **1st Class:** 62.9% survived
- **2nd Class:** 47.2% survived
- **3rd Class:** 24.2% survived

🔹 *Higher class passengers had better survival chances.*

---

### 2. Survival Rate by Gender

- **Female:** 74.2% survived
- **Male:** 18.9% survived

🔹 *Females had significantly higher survival rate — confirming 'women first' priority.*

---

### 3. Survival Rate by Port of Embarkation

- **Cherbourg (C):** 55.4% survived
- **Queenstown (Q):** 38.9% survived
- **Southampton (S):** 33.7% survived

🔹 *Passengers from Cherbourg had the highest survival rate.*

---

### 4. Correlation Matrix

- Fare has mild positive correlation with survival.
- Pclass and Fare have negative correlation.

---

### 5. Pairplot Analysis

- Clear visual separation of Pclass, Fare, and Survived.
- Fare increases with survival.
- Pclass 1 and females show better survival patterns.

---
### 6. Age Distribution by Survival

The following chart visualizes the age distribution of passengers, segmented by survival status (0 = did not survive, 1 = survived):
Insights
Age Demographics: Most passengers were aged 20–40, with a peak around 30 years, as seen in the histogram's concentration.
Survival Patterns:
Children (0–10 years): Young children had a higher survival rate, with a noticeable proportion of orange bars (survived) compared to blue bars (did not survive).
Young Adults (20–40 years): This age group, the largest in the dataset, had a higher proportion of non-survivors, indicating lower survival chances.
Older Passengers (50+ years): Survival rates dropped significantly for older passengers, with very few survivors above 60 years.
Density Trends: The KDE curves highlight that survival probability decreases with age, with a steeper decline for non-survivors.

These findings suggest that age played a role in survival outcomes, with children having a better chance of survival, possibly due to prioritization during evacuation.
## 📊 Visuals Used:

- Histograms
- Boxplots (Age, Fare)
- Pairplot
- Heatmap (correlation)
- Barplots
- Groupby summaries

---

## 🛠 Tools Used:

- Python (Pandas, Seaborn, Matplotlib)
- Google Colab

---

## ✅ Conclusion:
Exploratory Data Analysis revealed **strong relationships between Pclass, Sex, Fare, and Survival**. These insights are critical for building predictive models.

---

## 🔗 Dataset Source:
[Titanic - Kaggle Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

