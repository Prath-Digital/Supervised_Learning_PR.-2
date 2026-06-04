<div align="center">
	<img src="./assets/banner.png" alt="Project Banner" width="500"/>
</div>

# 🏠 Predictive Insight Engine

<div align="center">

<img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python"/>
<img src="https://img.shields.io/badge/License-Academic%20Use-green"/>
<img src="https://img.shields.io/badge/Status-Student%20Project-orange"/>

</div>

---

## 📚 Overview
Welcome to the **Predictive Insight Engine**! This project leverages supervised learning to predict house prices using real-world data and more advanced regression techniques than the [`Pr. 1`](https://github.com/Prath-Digital/Supervised_Learning_PR.-1). It is designed as a comprehensive academic submission, showcasing both conceptual understanding and practical implementation.

---

## 📝 Project Title
### 🎓 Predictive Insight Engine

---

## 👨‍🎓 Student Submission
> _This repository is submitted as part of coursework to demonstrate mastery of supervised learning, model evaluation, and optimization._

---

## 🎯 Objective
Design, implement, analyze, and evaluate multiple supervised learning models to predict house prices based on various features. The project emphasizes:

- 📈 Linear & Polynomial Regression
- ⚙️ Gradient Descent Optimization
- 🧠 Model Performance Analysis (Bias-Variance, Overfitting, Underfitting)

---

## 🏢 Problem Statement
You are working as a **Machine Learning Engineer** at a real estate analytics company. The company already uses a basic regression model to predict **house prices**, but it suffers from **overfitting and unstable predictions** across different datasets.

Your task is to build a **robust regression pipeline** that:

- Applies **regularization techniques**
- Uses **proper cross-validation strategies**
- Compares **linear and non-linear regression models**
- Selects the **best-performing model** based on validation performance

The final solution must generalize well on unseen data.

---

## 📂 Repository Structure

```text
├── .git/                                                # Git version control
├── assets/
│   └── banner.png                                       # Project banner image
├── data/
│   └── Advanced_Regression_HousePrice_Dataset_3800.csv  # Dataset
├── LICENSE                                              # License info
├── project.ipynb                                        # Main Jupyter notebook (code, analysis, visualizations)
├── README.md                                            # Project documentation
├── requirements.txt                                     # Python dependencies
├── summary-report.pdf                                   # Final summary report (if provided)
└── theory-concepts.pdf                                  # Conceptual answers (if provided)
```

---

## 📊 Results & Analysis
- **Best Model:** Multiple Linear Regression (MLR) provided the best balance of bias and variance, outperforming Simple Linear Regression (SLR) and Polynomial Regression (PR) in most cases.
- **Gradient Descent:** Custom implementations of Batch, Stochastic, and Mini-Batch Gradient Descent were compared for convergence speed and accuracy.
- **Overfitting/Underfitting:** Polynomial Regression showed signs of overfitting at higher degrees, while SLR underfit the data. MLR achieved the best generalization.
- **Business Interpretation:** The models help estimate house prices, supporting better decision-making for real estate analytics.

---


---

## 🛠️ Installation & Usage

**1. Clone the repository:**

```bash
git clone https://github.com/Prath-Digital/Supervised_Learning_PR.-2.git
cd Supervised_Learning_PR.-2
```

**2. Install dependencies:**

```bash
pip install -r requirements.txt
```

**3. Run the notebook:**

Open `project.ipynb` in Jupyter Notebook or VS Code and execute the cells sequentially.

---


## 📚 References & Resources
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---


## ✅ Submission Checklist
- [x] Source code (`project.ipynb`)
- [x] Model evaluation results
- [x] Graphs and plots
- [x] Summary report (`summary-report.pdf`)
- [x] Conceptual answers (`theory-concepts.pdf`)

---


## 📧 Contact
For any queries, please contact the student or faculty as per submission guidelines.

---

## © License
This project is for academic purposes only. See [`LICENSE`](./LICENSE) for details.