# 📊 Dataset

**Source:** `Iris.csv`
**Records:** 150 samples (50 per species)

### Features:

| Feature | Description | Type |
|---------|-------------|------|
| `Id` | Sample identifier | Integer |
| `SepalLengthCm` | Sepal length in centimeters | Float |
| `SepalWidthCm` | Sepal width in centimeters | Float |
| `PetalLengthCm` | Petal length in centimeters | Float |
| `PetalWidthCm` | Petal width in centimeters | Float |
| `Species` | Iris flower species | String |

### Species Classes:

- 🔵 **Iris-setosa** (50 samples)
- 🟠 **Iris-versicolor** (50 samples)
- 🔴 **Iris-virginica** (50 samples)

---

## 🔍 Analysis Performed

### 🔢 Data Inspection

```python
df.shape        # Dataset dimensions
df.columns      # Feature names
df.head()       # First 5 rows
df.info()       # Data types and non-null counts
df.describe()   # Statistical summary
```

---

## 2️⃣ Visualizations Created

| Plot Type | Purpose | Key Insight |
|-----------|---------|-------------|
| Scatter Plot | Sepal/Petal relationships | Species form distinct clusters |
| Histogram | Feature distributions | Petal features show bimodal patterns |
| Box Plot | Compare features by species | Minimal outliers; clear median differences |
| Pair Plot | Multi-feature overview | Petal dimensions best separate species |
| Heatmap | Feature correlations | PetalLength ↔ PetalWidth: r ≈ 0.96 |

## 3️⃣ Code Structure (Labelled Cells)

1. Cell 1: Imports
2. Cell 2: Load & display dataset
3. Cell 3: .shape, .columns, .head()
4. Cell 4: Scatter plot (Sepal dimensions)
5. Cell 5: Histogram (All features)
6. Cell 6: Box plot (By species)
7. Cell 7: Scatter plot (Petal dimensions)
8. Cell 8: Pair plot (Advanced view)
9. Cell 9: Correlation heatmap

---

## 💡 Key Insights

- ✅ **Data Quality:** No missing values, no duplicates, perfectly balanced classes
- ✅ **Feature Correlation:** Petal length and width are highly correlated (r > 0.95)
- ✅ **Species Separation:** Iris-setosa is perfectly separable using petal measurements
- ✅ **Classification Power:** Petal features are more discriminative than sepal features
- ✅ **Overlap Alert:** Iris-versicolor and Iris-virginica show some overlap in sepal space

---

## 📋 Statistical Summary (Numerical Features)

| Feature | Mean | Std | Min | Max |
|---------|------|-----|-----|-----|
| SepalLengthCm | 5.84 | 0.83 | 4.3 | 7.9 |
| SepalWidthCm | 3.05 | 0.43 | 2.0 | 4.4 |
| PetalLengthCm | 3.76 | 1.76 | 1.0 | 6.9 |
| PetalWidthCm | 1.20 | 0.76 | 0.1 | 2.5 |

---

## 🌍 Real-World Relevance

- 💠 **Foundation for ML:** Clean EDA ensures better model performance
- 💠 **Feature Selection:** Identifies which variables matter most for classification
- 💠 **Data Storytelling:** Visualizations help communicate insights to non-technical stakeholders
- 💠 **Problem-Solving:** Understanding distributions aids in outlier detection and data cleaning

---

## ✅ Conclusion

This project demonstrates the power of **Exploratory Data Analysis** in uncovering hidden patterns before building machine learning models.

---

## 👤 Author

**Amjad Hassan**
Student ID: DHC-1292

💬 For questions or collaboration, feel free to connect!

---

## 📋 Project Details

- **Created:** 2026
- **Python Version:** 3.13+
- **Environment:** Virtual Environment (.venv)
- **License:** Educational Use