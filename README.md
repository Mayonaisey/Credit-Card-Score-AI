# Credit-Card-Score-AI

A machine learning project designed to predict whether a credit card applicant is a **"good"** or **"bad"** client based on personal and financial data. This project simulates a credit scoring system used in real-world banking to assess credit risk.

---

## 🎯 Objective

To build a credit scoring model that can:
- Predict an applicant's likelihood of default
- Help financial institutions make informed decisions on credit issuance
- Optimize predictive performance using feature selection and hyperparameter tuning

---

## 🧩 Project Workflow

1. **Data Preprocessing**  
   - Handled missing values, encoding categorical variables, and normalization.
2. **Feature Selection**  
   - Used a **Genetic Algorithm (GA)** to select the most informative subset of features.
3. **Model Training**  
   - Trained multiple models:  
     - K-Nearest Neighbors (KNN)  
     - Multi-Layer Perceptron (MLP)  
     - Decision Tree Classifier
4. **Hyperparameter Tuning**  
   - Used **GridSearchCV** for systematic parameter optimization.
5. **Evaluation & Testing**  
   - Best performance achieved with **Decision Tree**, with an accuracy of **75.84%** on the test set.

---

## 📊 Models & Performance

| Model           | Accuracy (%) |
|----------------|--------------|
| KNN            | ~74.52%         |
| MLP            | ~75.8%         |
| Decision Tree  | **75.84**    |

---

## ⚙️ Tech Stack

- **Language**: Python 3.x  
- **Libraries**:
  - `sklearn`
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `pygad` (for Genetic Algorithm)

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mayonaisey/Credit-Card-Score-AI.git
   cd Credit-Card-Score-AI
