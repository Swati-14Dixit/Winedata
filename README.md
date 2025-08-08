# 🍷 Wine Quality Analysis

A complete end-to-end analysis of red wine quality based on physicochemical properties using Python. This project includes data exploration, correlation analysis, visualization, and wine quality prediction using machine learning models.

---

## 📁 Dataset

The dataset used is the **Red Wine Quality** dataset from the UCI Machine Learning Repository. It contains various chemical attributes of red wines and quality ratings (0–10) based on sensory evaluation.

Each row represents a wine sample with the following features:
- Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar
- Chlorides, Free Sulfur Dioxide, Total Sulfur Dioxide
- Density, pH, Sulphates, Alcohol
- Quality (Target variable)

📌 [Download the dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
OR use the uploaded file for reference. 

---

## 🧠 Key Questions Addressed

1. **General Characteristics**
   - What is the most frequent wine quality score?
   - What are the highest and lowest quality scores?

2. **Correlation Analysis**
   - How are fixed acidity, alcohol, and free sulfur dioxide related to wine quality?

3. **Residual Sugar Analysis**
   - How does residual sugar vary between best and worst quality wines?

4. **Impact of Volatile Acidity**
   - Is there a relationship between volatile acidity and wine quality?

5. **Predicting Wine Quality**
   - Build ML models using:
     - Decision Tree Classifier
     - Random Forest Classifier
   - Compare model accuracy and visualize feature importance.

---

## 📊 Key Results

| Task | Result |
|------|--------|
| Most Frequent Quality | 5 |
| Highest Quality | 8 |
| Lowest Quality | 3 |
| Alcohol & Quality Correlation | **0.476** (moderate positive) |
| Fixed Acidity & Quality | 0.124 (weak positive) |
| Free SO₂ & Quality | -0.051 (very weak negative) |
| Avg Residual Sugar (Quality 8) | 2.58 g/L |
| Avg Residual Sugar (Quality 3) | 2.64 g/L |
| Volatile Acidity | Inversely correlated with quality |
| Decision Tree Accuracy | 55.94% |
| Random Forest Accuracy | **65.94%** (better model) |

---

## 📈 Visualizations

- Correlation heatmaps
- Boxplots for volatile acidity
- Scatter plots for acidity, alcohol, and sulfur dioxide
- Feature importance bar charts (ML models)

---

## 🧾 How to Use

1. **Open the Colab notebook** here:  
   [![Open In Colab](https://colab.research.google.com/drive/1tymKBkFhVA3AT8CNJ5RrhD1pIxNsnKNb#scrollTo=SFr0bygYTjzN)

2. **Upload** the `wine_data.csv` file (from Kaggle or UCI).

3. **Run all cells** sequentially to perform analysis and modeling.

---

## 📦 Libraries Used

- `pandas` – data manipulation  
- `numpy` – numerical analysis  
- `matplotlib` & `seaborn` – data visualization  
- `scikit-learn` – machine learning models

---

## 📄 Deliverables

- ✅ Summary of findings for all questions
- ✅ Code snippets in Python
- ✅ Visualizations for interpretation
- ✅ ML model accuracy comparison
- ✅ Final report (Word/Colab output)

---

## 📬 Contact

For feedback or suggestions, feel free to raise an issue or reach out via GitHub.

---

> 🚀 This project is beginner-friendly and a great example of applying real-world data analysis techniques to a public dataset.
