# DSAI-IIIT-Sem1: Data Science Lab Assignments & Notebooks

> A comprehensive collection of Data Science Lab assignments and supervised learning demonstrations from IIIT's Semester 1 curriculum.

**Course:** Data Science Lab (Sem-1)  
**Institution:** IIIT (Indian Institute of Information Technology)  
**Student:** Debarun Ghosh (ID: 25MDA294)  
**Last Updated:** 2026-06-13

---

## 📋 Overview

This repository contains practical assignments and learning notebooks that cover fundamental and intermediate data science concepts, including Python programming, data preprocessing, and supervised learning models.

### Key Focus Areas:
- **Python Fundamentals** — Control flow, functions, recursion, data structures
- **Data Preprocessing** — Normalization, standardization, handling missing values, categorical encoding
- **Machine Learning** — Linear regression, random forests, model evaluation
- **Real-World Datasets** — Wine quality, heart disease prediction, weather patterns, housing prices

---

## 📁 Repository Structure

```
DSAI-IIIT-Sem1/
├── DSLab_Assgn1_Debarun_25MDA294.ipynb       # Python fundamentals & control flow
├── DSLab_Assgn2_Debarun_25MDA294.ipynb       # Advanced Python & data structures
├── DSLab_Assgn3_Debarun_25MDA294.ipynb       # Data manipulation & visualization
├── DSLab_Assgn4_Debarun_25MDA294.ipynb       # Data preprocessing & scaling
├── DSLab_Assgn5_Debarun_25MDA294.ipynb       # Feature engineering
├── DSLab_Assgn6_Debarun_25MDA294.ipynb       # Statistical analysis
├── DSLab_Assgn7_Debarun_25MDA294.ipynb       # Advanced ML techniques
├── supervised_learning_housing.ipynb         # Supervised learning demo
├── assgn4-data/                              # Datasets directory
│   ├── wine_data.csv                         # Wine quality dataset (178 samples, 13 features)
│   ├── heart_disease_uci.csv                 # Heart disease diagnosis dataset
│   └── weatherAUS.csv                        # Australian weather dataset
├── apple.png                                 # Sample image file
├── sample_audio.wav                          # Sample audio file
└── README.md                                 # This file
```

---

## 📚 Assignment Details

### Assignment 1: Core Python Programming Skills
**Objective:** Strengthen fundamental Python programming through:
- Conditional logic & control flow
- Loops & pattern generation
- Functions & recursion
- Lists & dictionaries manipulation
- Problem-solving & mini challenges

**Duration:** 2 hours  
**Key Topics:**
- Prime number checking and factor analysis
- Number classification (even/odd, positive/negative)
- Pattern generation with loops
- Function design and implementation

---

### Assignment 2: Advanced Python Programming
**Objective:** Deepen Python skills with:
- Complex data structures
- String manipulation
- Lambda functions and list comprehensions
- File I/O operations
- Module implementation

---

### Assignment 3: Data Manipulation & Visualization
**Objective:** Master data exploration and visualization:
- Data loading and exploration
- Statistical summaries
- Visualization techniques (matplotlib, seaborn)
- Data cleaning fundamentals

---

### Assignment 4: Data Preprocessing & Normalization
**Objective:** Apply essential preprocessing techniques:

**Part 1 - Wine Dataset:**
- Min-Max Normalization (scale to [0, 1])
- Z-score Standardization (mean=0, std=1)
- Feature scaling comparison and visualization
- Dataset: 178 samples, 13 features, 3 wine classes

**Part 2 - Heart Disease Dataset:**
- Handling missing values (imputation strategies)
- Categorical encoding techniques
- Feature importance analysis

**Part 3 - Weather Dataset:**
- Time-series data preprocessing
- Outlier detection and treatment
- Data validation and quality checks

---

### Assignment 5: Feature Engineering
**Objective:** Create and select meaningful features:
- Feature creation and transformation
- Feature selection methods
- Feature importance analysis
- Handling imbalanced data

---

### Assignment 6: Statistical Analysis
**Objective:** Apply statistical methods:
- Descriptive statistics
- Hypothesis testing
- Correlation analysis
- Probability distributions

---

### Assignment 7: Advanced ML Techniques
**Objective:** Implement sophisticated ML approaches:
- Ensemble methods
- Cross-validation strategies
- Hyperparameter tuning
- Model comparison and selection

---

## 🏠 Supervised Learning Demo: Housing Price Prediction

**Dataset:** California Housing (scikit-learn built-in)  
**Goal:** Predict median house prices using regression models

### Models Implemented:
1. **Linear Regression**
   - Simple, interpretable model
   - Assumes linear relationship between features and target
   - Fast training and prediction

2. **Random Forest Regressor**
   - Ensemble method combining multiple decision trees
   - Captures complex non-linear relationships
   - Reduces overfitting through bagging

### Evaluation Metrics:
- **MAE (Mean Absolute Error):** Average absolute difference between predicted and actual values
- **MSE (Mean Squared Error):** Average squared difference (penalizes larger errors)
- **R² Score:** Proportion of variance explained by the model (0 to 1 scale)

### Workflow:
1. Load and explore the California Housing dataset
2. Preprocess data and split into train/test sets
3. Feature standardization using StandardScaler
4. Train Linear Regression model
5. Train Random Forest Regressor model
6. Compare model performance
7. Visualize predictions vs actual values

---

## 📊 Datasets

### 1. Wine Quality Dataset (`wine_data.csv`)
- **Samples:** 178
- **Features:** 13 (Alcohol, Malic Acid, Ash, etc.)
- **Classes:** 3 wine types
- **Use Case:** Classification & preprocessing practice

### 2. Heart Disease UCI (`heart_disease_uci.csv`)
- **Features:** Patient health indicators
- **Target:** Heart disease diagnosis
- **Use Case:** Missing value handling, categorical encoding

### 3. Weather Australia (`weatherAUS.csv`)
- **Type:** Time-series weather data
- **Features:** Temperature, humidity, rainfall, etc.
- **Use Case:** Outlier detection, temporal analysis

---

## 🛠 Technologies & Libraries

### Core Libraries:
```python
- pandas          # Data manipulation and analysis
- numpy           # Numerical computing
- scikit-learn    # Machine learning algorithms
- matplotlib      # Static visualizations
- seaborn         # Statistical graphics
```

### Optional Libraries:
```python
- jupyter         # Interactive notebooks
- scipy           # Scientific computing
- statsmodels     # Statistical modeling
```

---

## 🚀 Getting Started

### Prerequisites:
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- pip or conda package manager

### Installation:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/debarun1234/DSAI-IIIT-Sem1.git
   cd DSAI-IIIT-Sem1
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open any notebook:**
   - Click on any `DSLab_Assgn*.ipynb` file
   - Run cells sequentially using Shift+Enter

### Alternative: Google Colab
Upload the notebooks directly to [Google Colab](https://colab.research.google.com/) to run without local installation.

---

## 💡 Learning Path

### Recommended Sequence:
1. **Start with Assignment 1-3** → Build Python fundamentals
2. **Progress to Assignment 4** → Learn data preprocessing
3. **Assignment 5-6** → Feature engineering & statistics
4. **Assignment 7** → Advanced techniques
5. **Supervised Learning Demo** → Apply knowledge to real ML task

---

## 📈 Key Concepts Covered

- **Python Programming:** Control flow, functions, OOP basics, file handling
- **Data Science Libraries:** pandas, numpy, scikit-learn workflows
- **Data Preprocessing:** Normalization, standardization, missing value treatment
- **Visualization:** Distribution plots, scatter plots, heatmaps
- **Machine Learning:** Regression, classification, model evaluation
- **Statistics:** Descriptive stats, hypothesis testing, correlation analysis

---

## 📝 Notes & Tips

### For Running the Notebooks:
- Execute cells sequentially for proper variable dependencies
- Some notebooks require datasets from `assgn4-data/` directory
- Pay attention to markdown cells for explanations and requirements
- Comments explain the "why" behind each implementation

### Best Practices Demonstrated:
- Clear variable naming and code organization
- Function documentation and comments
- Data validation before processing
- Proper model evaluation techniques
- Visualization for insights

---

## 🤝 How to Use This Repository

1. **Learn from Examples** — Study implementations of various data science concepts
2. **Practice on Datasets** — Use provided datasets to practice preprocessing and ML
3. **Reference Solutions** — Check notebooks when stuck on similar problems
4. **Build Upon** — Modify assignments to explore different techniques
5. **Share & Collaborate** — Fork, extend, and contribute improvements

---

## 📖 Additional Resources

### Official Documentation:
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Scikit-learn Guide](https://scikit-learn.org/stable/)
- [NumPy Reference](https://numpy.org/doc/)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index)

### Learning Platforms:
- [Kaggle Learn](https://www.kaggle.com/learn)
- [DataCamp](https://www.datacamp.com/)
- [Coursera ML Courses](https://www.coursera.org/)

---

## 📧 Contact & Attribution

**Author:** Debarun Ghosh  
**Student ID:** 25MDA294  
**Institution:** IIIT  
**Repository:** [github.com/debarun1234/DSAI-IIIT-Sem1](https://github.com/debarun1234/DSAI-IIIT-Sem1)

---

## 📄 License

This repository contains educational material from IIIT coursework. Use for learning purposes.

---

## 🎯 What You'll Learn

By working through this repository, you'll gain proficiency in:
- ✅ Python fundamentals and advanced programming
- ✅ Data exploration and visualization
- ✅ Data preprocessing and feature engineering
- ✅ Statistical analysis and hypothesis testing
- ✅ Building and evaluating machine learning models
- ✅ Working with real-world datasets
- ✅ Best practices in data science workflow

---

**Last Updated:** June 13, 2026  
**Version:** 1.0  
**Status:** Complete Assignment Series
