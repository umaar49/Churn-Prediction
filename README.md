# churn-prediction-ann

This project predicts whether a customer will churn (leave a service) based on their historical profile and usage data. It includes data preprocessing, class imbalance handling, neural network model training using TensorFlow/Keras, and performance evaluation.

---

## 📂 Project Structure

- `churn_ann_model.ipynb` – Full Jupyter Notebook with preprocessing, model training, and evaluation
- `README.md` – Project overview and guide
- `dataset.csv` – Dataset used for training the model *(if available)*

---

## 📊 Dataset Overview

The dataset contains customer data, which includes:

- Features like  tenure, contract type, monthly charges, and other customer service usage info
- Target column: `Churn` (Yes = customer left, No = customer stayed)

After preprocessing:
- Handled missing and categorical values
- Scaled features for better model performance
- Addressed class imbalance using SMOTE

> 📌 **Dataset Source:**  
> Public churn dataset (e.g., [Kaggle Telco Churn](https://www.kaggle.com/blastchar/telco-customer-churn))  
> *(Used for educational purposes only)*

---

## 🔍 Exploratory Data Analysis (Optional)

- Distribution of churn vs non-churn customers
- Histograms and box plots to understand feature impact on churn

---

## 🧠 Model Used

- **Model:** Artificial Neural Network (ANN)
- **Architecture:**
  - Input: 26 features
  - Hidden Layers: 64 → 32 neurons (ReLU activation)
  - Output Layer: 1 neuron (Sigmoid activation)
- **Loss Function:** Binary Crossentropy
- **Optimizer:** Adam 

### 📉 Evaluation:

- Accuracy: ~82%
- Binary classification metrics (Confusion matrix, Precision, Recall planned for future versions)

---

## 🛠️ Tools & Technologies

- Python (NumPy, Pandas)
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook
- Matplotlib / Seaborn (for optional visualizations)

---

## 📌 Key Takeaways

- Implemented a full deep learning pipeline from raw data to predictions
- Handled imbalanced data with SMOTE
- Learned the impact of architecture and optimizer tuning on model performance
- Practiced good DL workflow using preprocessing, modeling, and evaluation

---

## 📫 Contact

**Muhammad Umar Saleem**  
Electrical Engineering Graduate (June 2025)  
Aspiring Data Scientist | Machine Learning Enthusiast  
