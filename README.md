# Machine Learning Projects

A collection of end-to-end machine learning notebooks covering classification, regression, clustering, and dimensionality reduction — implemented from scratch on real-world-style datasets using Python's core data science stack. This repository is a hands-on portfolio of classical ML algorithms, built while learning and applying supervised and unsupervised learning techniques to practical problems in healthcare, finance, marketing, and manufacturing.

---

## 📌 About This Repository

Each notebook in this repo is a self-contained ML project: it loads a dataset, performs exploratory data analysis (EDA) and preprocessing, trains one or more models, evaluates performance, and (in most cases) visualizes the results. The goal of this repository is to demonstrate:

- A working understanding of **core ML algorithms** — not just calling `.fit()`, but understanding *why* a given algorithm fits a given problem
- Comfort across the full **ML workflow**: data cleaning → feature engineering → model training → evaluation → interpretation
- Applied experience with **classification, regression, and clustering** problems across different domains
- Practical use of **Python's data science ecosystem** (NumPy, Pandas, Scikit-learn, Matplotlib/Seaborn)

This is a learning-in-public repository — every notebook was built to deepen understanding of a specific algorithm or technique by applying it to a real dataset rather than a toy example.

---

## 🗂️ Repository Structure

| Notebook | Algorithm | Problem Type | Domain / Use Case |
|---|---|---|---|
| `Email_Spam_Detection_using_Logistic_Regression.ipynb` | Logistic Regression | Binary Classification | Email spam filtering |
| `Email_Spam_Detection_using_Multinomial_Naive_Bayes.ipynb` | Multinomial Naive Bayes | Binary Classification | Email spam filtering (text/NLP-based) |
| `spam_ham_detection_using_navie_bayes.ipynb` | Naive Bayes | Binary Classification | Spam/ham message classification |
| `Spam_Ham_Prediction_Using_KNN.ipynb` | K-Nearest Neighbors | Binary Classification | Spam/ham message classification |
| `Spam_ham_Prediction_Using_SVM.ipynb` | Support Vector Machine | Binary Classification | Spam/ham message classification |
| `Indian_Liver_Patient_Prediction_Using_Decision_Tree_Classifier.ipynb` | Decision Tree | Binary Classification | Liver disease diagnosis prediction |
| `Indian_Liver_Patient_Prediction_Using_KNearest_Neighbors.ipynb` | K-Nearest Neighbors | Binary Classification | Liver disease diagnosis prediction |
| `Indian_Liver_Patient_using_Logistic_Regression.ipynb` | Logistic Regression | Binary Classification | Liver disease diagnosis prediction |
| `SVM_On_Liver_Patient_Dataset.ipynb` | Support Vector Machine | Binary Classification | Liver disease diagnosis prediction |
| `Online_Fraud_Detection_Using_Random_Forest.ipynb` | Random Forest | Binary Classification | Financial fraud detection |
| `Mall_Customer_Prediction_Using_KMeans_Clustering.ipynb` | K-Means Clustering | Unsupervised / Clustering | Customer segmentation |
| `k_means_heart_disease_analysis.ipynb` | K-Means Clustering | Unsupervised / Clustering | Heart disease risk grouping |
| `WineQuality_Prediction_Using_PCA.ipynb` | Principal Component Analysis | Dimensionality Reduction | Wine quality analysis |
| `Manufacturing_Predicition_Using_Polynomial_Regression.ipynb` | Polynomial Regression | Regression | Manufacturing output prediction |
| `Salary_Prediction_Using_LinearRegression.ipynb` | Linear Regression | Regression | Salary prediction based on experience |
| `simple_linear_regression_height_weight.ipynb` | Simple Linear Regression | Regression | Height–weight relationship modeling |

> Notebooks are grouped by problem domain in the table above for readability; in the repo itself they sit flat at the root for easy access.

---

## 🧠 Algorithms Covered

**Supervised Learning — Classification**
- Logistic Regression
- Naive Bayes (Multinomial)
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)
- Decision Tree Classifier
- Random Forest Classifier

**Supervised Learning — Regression**
- Simple & Multiple Linear Regression
- Polynomial Regression

**Unsupervised Learning**
- K-Means Clustering
- Principal Component Analysis (PCA)

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Core Libraries:**
  - `pandas`, `numpy` — data manipulation and numerical computation
  - `scikit-learn` — model implementation, preprocessing, evaluation metrics
  - `matplotlib`, `seaborn` — data visualization and exploratory analysis

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3.8+ and Jupyter installed.

```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

### Running the Notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/VemuriPavanateja2007/Machine-Learning.git
   cd Machine-Learning
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open any `.ipynb` file and run the cells sequentially (`Shift + Enter`) to reproduce the analysis, from data loading through model evaluation.

> Note: Some notebooks expect a dataset file (CSV) to be present in the working directory or loaded from a public source cited within the notebook. If a dataset is missing, check the first few cells of the notebook for the data source/link.

---

## 📊 Workflow Followed in Each Notebook

Every notebook in this repo follows a consistent, structured ML pipeline:

1. **Data Loading** — importing the dataset and inspecting its shape, types, and basic statistics
2. **Exploratory Data Analysis (EDA)** — visualizing distributions, correlations, and class balance
3. **Data Preprocessing** — handling missing values, encoding categorical variables, feature scaling
4. **Train-Test Split** — separating data to evaluate generalization performance
5. **Model Training** — fitting the relevant algorithm to the training data
6. **Evaluation** — assessing performance using metrics appropriate to the problem (accuracy, precision/recall, confusion matrix for classification; R², MAE/MSE for regression; inertia/silhouette for clustering)
7. **Visualization of Results** — plotting decision boundaries, clusters, regression lines, or confusion matrices where applicable

---

## 🎯 Purpose & Learning Outcomes

This repository was built to strengthen practical, hands-on machine learning skills by implementing algorithms across varied problem types rather than relying on a single canonical dataset. Working through these projects reinforced:

- How to choose an appropriate algorithm for a given data structure and problem type
- The trade-offs between model interpretability and performance (e.g., Logistic Regression vs. Random Forest)
- How to properly evaluate classification vs. regression vs. clustering models using the right metrics
- End-to-end data science workflow discipline — from raw data to a validated, interpretable model

---

## 🔭 Future Improvements

- [ ] Add a `requirements.txt` for reproducible environments
- [ ] Add dataset sources/links directly in this README for each notebook
- [ ] Consolidate notebooks into topic-based folders (`classification/`, `regression/`, `clustering/`)
- [ ] Add a model comparison notebook benchmarking algorithms on shared datasets (e.g., all liver-patient models side by side)
- [ ] Convert key notebooks into reusable Python modules/scripts

---

## 👤 Author

**Vemuri Venkata Satya Markandeya Pavanateja**
Final-year B.Sc Artificial Intelligence student, Government College (Autonomous), Rajahmundry

- LinkedIn: [linkedin.com/in/vemurivenkata-satya-markandeyapavanateja-0651a0403](https://www.linkedin.com/in/vemurivenkata-satya-markandeyapavanateja-0651a0403)
- Email: pavanatejavemuri2007@gmail.com

---

## 📄 License

This repository does not currently specify a license. If you'd like others to freely use, modify, or build on this work, consider adding an [MIT License](https://choosealicense.com/licenses/mit/) — it's the most common choice for educational ML repositories.

---

⭐ If you find this repository useful for learning ML concepts, consider giving it a star!
