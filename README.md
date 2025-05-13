# 🧠 Analyze Death Age Difference of Right-Handers vs. Left-Handers

This project investigates the difference in average age at death between right-handed and left-handed individuals using statistical analysis in Python.

---

## 📌 Objective

To explore whether handedness (left or right) has any statistically significant impact on lifespan. This includes:

- Calculating and comparing average age at death by handedness
- Visualizing the distributions
- Applying statistical tests to validate the findings
- Exploring Bayesian inference for probabilistic insights

---

## 📊 Dataset

- Dataset used: `death_hand_data.csv` *(or whatever the file name is)*
- Columns include:
  - `Handedness` – left or right
  - `AgeAtDeath` – age when the individual died

> Source: [Insert dataset source or say "synthetic/mock dataset created for study"]

---

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas
- NumPy
- Matplotlib / Seaborn
- SciPy (for hypothesis testing)
- PyMC / Bambi / ArviZ *(if you used Bayesian modeling)*

---

## 📈 Key Steps

1. **Data Cleaning**: Checked for nulls, data types, and outliers
2. **Exploratory Data Analysis (EDA)**:
   - Visualized age distribution for left vs. right-handers
   - Computed summary statistics
3. **Statistical Testing**:
   - Used independent t-test to compare mean ages
   - Bayesian inference for a probabilistic understanding (if applicable)
4. **Conclusion**:
   - Highlighted any significant difference in death age between groups

---

## 📷 Visualizations

*(You can upload and show charts or distribution plots here)*

```python
# Example Python snippet
sns.histplot(data=df, x="AgeAtDeath", hue="Handedness", kde=True)
