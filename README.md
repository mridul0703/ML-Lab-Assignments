# 🧪 Iris Dataset – Analysis Notebook
<br/>
<div align="center">

  <!-- Tech Stack Badges -->
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-Data%20Frames-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-Iris%20Dataset-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Numerical-013243?style=for-the-badge&logo=numpy&logoColor=white" /><br/>
</div>

<br/>
A concise Jupyter notebook demonstrating data loading, inspection, cleaning, and label mapping on the classic Iris dataset using `pandas` and `scikit-learn`. Ideal as a quick reference or a starting point for ML experimentation.

---

## 🚀 Features

- 📥 Load Iris dataset into a tidy `pandas` DataFrame
- 🔎 Print feature names, class names, and dataset shapes
- 🧼 Basic data validation (missing values) and consistent column renaming
- 🏷️ Human-readable species names with verified label mapping (0/1/2)
- 👀 Quick preview of the first five processed rows

---

## 🛠️ Tech Stack

- **Python** (3.10+)
- **Jupyter Notebook**
- **pandas** for data handling
- **scikit-learn** for dataset access
- **NumPy** (implicit dependency)

---

## 📁 Folder Structure

```
ml-iris/
|
├── iris_analysis.ipynb   # Main analysis notebook
└── README.md             # This file
```

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
https://github.com/mridul0703/ML-Lab-Assignments.git
cd ML-Lab-Assignments
```

### 2. (Recommended) Create a Virtual Environment
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1  # Windows PowerShell
```

### 3. Install Dependencies
```bash
pip install jupyter pandas scikit-learn
```

### 4. Run the Notebook
```bash
jupyter notebook iris_analysis.ipynb
```
Open in your browser and run cells top-to-bottom.

---

## 📓 Notebook Overview

The notebook is structured into simple, focused steps:

1. Load dataset (150 samples, 4 numeric features)
2. Print feature names and class names
3. Show shapes of `X`, `y`, and combined `df`
4. Validate data (missing values) and standardize column names
5. Map numeric labels ↔ species names (`setosa`, `versicolor`, `virginica`)
6. Display the first five rows of the processed DataFrame

---

## 📊 Key Outputs

- **Loaded**: 150 rows × 5 columns
- **Features**: `sepal length (cm)`, `sepal width (cm)`, `petal length (cm)`, `petal width (cm)`
- **Classes**: `setosa`, `versicolor`, `virginica`
- **Shapes**: `X: (150, 4)`, `y: (150,)`, `df: (150, 5)`
- **Missing values**: None across all columns
- **Renamed columns**: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species_label`
- **Label mapping**: `0, 1, 2` ↔ `setosa, versicolor, virginica`

---

## 🧑‍💻 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📍 License

This project is licensed under the MIT License.

---

## 📬 Contact

For questions or collaborations: [mridulmkumar07@gmail.com]
