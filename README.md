# 🌌 Predicting Stars, Galaxies and Quasars Using Machine Learning

A machine learning classification project that uses astronomical data to identify and classify celestial objects into three categories: **Stars, Galaxies, and Quasars (QSOs)**.

The project implements and compares three supervised machine learning algorithms: Decision Tree, Logistic Regression, and K-Nearest Neighbors (KNN).

## 📌 Project Overview

Modern astronomical surveys generate massive amounts of observational data. Machine learning can help astronomers analyze this data and classify celestial objects based on their observed properties.

This project uses the **Star Classification Dataset** to build classification models capable of distinguishing between different astronomical objects.

## 🎯 Classification Categories

| Class Label | Astronomical Object |
|---|---|
| 0 | Galaxy (G) |
| 1 | Quasar (Q) |
| 2 | Star (S) |

## 📊 Dataset Features

The dataset contains astronomical measurements and observational properties, including:

- Right Ascension (RA)
- Declination (DEC)
- Ultraviolet filter (u)
- Green filter (g)
- Red filter (r)
- Infrared filters (i and z)
- Redshift
- Run, Rerun, Camcol and Field information
- Plate, MJD and Fiber ID

The object identification columns `obj_ID` and `spec_obj_ID` are removed before model training.

## ⚙️ Project Workflow

1. **Data Collection:** Load the astronomical dataset using Pandas.
2. **Data Exploration:** Inspect dataset dimensions, statistical summaries and missing values.
3. **Data Preprocessing:** Remove unnecessary identification columns.
4. **Label Encoding:** Convert categorical astronomical classes into numerical labels.
5. **Feature Scaling:** Apply StandardScaler to normalize feature values.
6. **Data Splitting:** Divide the dataset into 70% training data and 30% testing data.
7. **Model Training:** Train three supervised classification algorithms.
8. **Model Evaluation:** Evaluate predictions using accuracy, precision, recall and F1-score.
9. **Visualization:** Compare classification performance using Matplotlib and Seaborn.

## 🤖 Machine Learning Algorithms

### 1. Decision Tree Classifier
A tree-based supervised learning algorithm that makes classification decisions through a sequence of feature-based conditions.

### 2. Logistic Regression
A classification algorithm that estimates class probabilities and assigns observations to the appropriate category.

### 3. K-Nearest Neighbors (KNN)
A distance-based classification algorithm that identifies the class of a data point using its nearest neighboring observations.

## 📈 Model Performance Comparison

The following results were obtained from the classification experiments:

| Model | Accuracy |
|---|---:|
| Decision Tree | 95% |
| Logistic Regression | 96% |
| KNN Classifier | 90% |

**Best Performing Model:** Logistic Regression, with a reported accuracy of 96%.

## 📋 Evaluation Metrics

The models are evaluated using:

- **Accuracy:** Measures the proportion of correctly classified observations.
- **Precision:** Measures how many predicted observations belong to the correct class.
- **Recall:** Measures how many actual observations are correctly identified.
- **F1-score:** Balances precision and recall.

Classification reports and graphical visualizations are used to compare model performance.

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning algorithms |
| Jupyter Notebook | Development environment |

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Predicting-Stars-Galaxies-and-Quasars.git
```

### 2. Navigate to the project directory

```bash
cd Predicting-Stars-Galaxies-and-Quasars
```

### 3. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

### 4. Add the dataset

Place `star_classification.csv` in the project directory.

### 5. Run the notebook

```bash
jupyter notebook
```

Open `Predicting_Stars,_Galaxies_and_Quasars.ipynb` and execute the cells.

## 📂 Project Structure

```text
Predicting-Stars-Galaxies-and-Quasars/
│
├── Predicting_Stars,_Galaxies_and_Quasars.ipynb
├── star_classification.csv
└── README.md
```

## 🎓 Learning Objectives

- Understand supervised machine learning classification.
- Explore and preprocess astronomical datasets.
- Implement Decision Tree, Logistic Regression and KNN.
- Understand feature scaling and label encoding.
- Evaluate classification models using performance metrics.
- Visualize and compare multiple machine learning algorithms.
- Explore applications of machine learning in astronomy.

## 🔭 Future Improvements

- Experiment with Random Forest and Support Vector Machines.
- Implement hyperparameter tuning.
- Explore deep learning approaches.
- Perform cross-validation for more reliable evaluation.
- Investigate astronomical feature importance.

## 📝 Conclusion

This project demonstrates the application of supervised machine learning to astronomical object classification. By implementing and comparing three classification algorithms, it explores how computational techniques can help distinguish stars, galaxies and quasars from observational data.

It serves as a practical learning project at the intersection of **Machine Learning, Data Science and Astronomy (Astroinformatics)**.

---

**Made with Python | Machine Learning | Astronomy** 🌌
