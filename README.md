# 🧠 Customer Churn Prediction | Predicción de Abandono de Clientes

## 🇺🇸 English

### 📌 Project Overview
Customer churn is a major challenge in the banking industry. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project focuses on building a machine learning model to **predict which customers are likely to leave the bank**, enabling proactive retention strategies.

---

### 🎯 Objective
Develop a classification model that maximizes **F1-score** while handling class imbalance.

---

### 📊 Dataset Features
- Credit Score
- Geography
- Gender
- Age
- Balance
- Number of Products
- Estimated Salary
- Target: `Exited` (1 = churn, 0 = stay)

---

### ⚠️ Key Challenge: Class Imbalance
- ~80% customers stay
- ~20% customers leave

This imbalance makes accuracy misleading, so F1-score was prioritized.

---

### 🤖 Models Used
- Logistic Regression (baseline)
- Random Forest
- Hyperparameter tuning with GridSearchCV

---

### 🔧 Techniques Applied
- One-hot encoding
- Feature scaling
- Oversampling (minority class)
- Undersampling
- Model tuning

---

### 📈 Results

| Model | F1-score (Churn) | Recall (Churn) |
|------|----------------|---------------|
| Baseline | 0.36 | 0.25 |
| Oversampling | 0.62 | 0.56 |
| Final Model | **0.63** | **0.56** |

---

### 🚀 Key Insights
- Class imbalance significantly impacts model performance
- Oversampling improved churn detection by over 30%
- Random Forest outperformed Logistic Regression
- Final model successfully meets business requirement (F1 ≥ 0.59)

---

### 💼 Business Impact
- Enables early detection of at-risk customers
- Supports targeted retention campaigns
- Reduces customer acquisition costs

---

### 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## ES Español

### 📌 Descripción del Proyecto
La pérdida de clientes (churn) es uno de los principales problemas en la banca. Retener clientes existentes es más barato que adquirir nuevos.

Este proyecto desarrolla un modelo de Machine Learning para **predecir qué clientes tienen riesgo de abandonar el banco**.

---

### 🎯 Objetivo
Construir un modelo de clasificación optimizando el **F1-score**, considerando el desbalance de clases.

---

### ⚠️ Desafío principal
- ~80% clientes se quedan
- ~20% clientes se van

Esto hace que la accuracy sea engañosa, por lo que se prioriza F1-score.

---

### 🤖 Modelos utilizados
- Regresión Logística (baseline)
- Random Forest
- Optimización con GridSearch

---

### 🔧 Técnicas aplicadas
- Codificación de variables categóricas
- Escalado de variables
- Oversampling
- Undersampling
- Ajuste de hiperparámetros

---

### 📈 Resultados

| Modelo | F1-score (Churn) | Recall |
|------|----------------|--------|
| Base | 0.36 | 0.25 |
| Oversampling | 0.62 | 0.56 |
| Modelo final | **0.63** | **0.56** |

---

### 🚀 Insights clave
- El desbalance afecta significativamente el rendimiento
- Oversampling mejora la detección de clientes en riesgo
- Random Forest supera a modelos lineales
- El modelo cumple el objetivo del negocio

---

### 💼 Impacto de negocio
- Permite detectar clientes en riesgo
- Facilita campañas de retención
- Reduce costos de adquisición

---

### 🛠 Tecnologías
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
