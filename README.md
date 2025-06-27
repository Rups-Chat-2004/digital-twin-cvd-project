# Digital Twin for Cardiovascular Disease Prediction using ACO, SMOTE, CNN & Bayesian Optimization

This project aims to build a **Digital Twin system for predicting Cardiovascular Diseases (CVD)** using a hybrid machine learning approach:
- **ACO (Ant Colony Optimization)** for feature selection
- **SMOTE** for data balancing
- **CNN** for classification
- **Bayesian Optimization** for hyperparameter tuning

---

##  Files Included

- `digital-twin-for-cvd-using-aco-smote-cnn-bo.ipynb` – Jupyter notebook with all steps
- `new dataset.csv` – The dataset (CVD-related) used in the project

---

##  Dataset

The dataset used is **"Heart Disease Dataset (Comprehensive)"**, originally sourced from [Kaggle](https://www.kaggle.com/datasets/sid321axn/heart-statlog-cleveland-hungary-final). It has been preprocessed and doubled for SMOTE operations.

---

##  Libraries and Frameworks Used

- **Pandas** & **NumPy** – For data manipulation and preprocessing
- **Scikit-learn** – For ML utilities, evaluation, and train/test splitting
- **Imbalanced-learn (SMOTE)** – For handling imbalanced datasets
- **DEAP** – For implementing Ant Colony Optimization
- **TensorFlow/Keras** – For building and training the CNN model
- **Scikit-Optimize (skopt)** – For Bayesian hyperparameter optimization

---

##  How to Run

1. Clone the repo or download the ZIP
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

--

##  Sample Output 

![Test Accuracy](https://github.com/user-attachments/assets/0ee92843-46ae-43e3-94c8-729a43b79d9e)


![Confusion Matrix](https://github.com/user-attachments/assets/8f37b5f2-491f-46a3-a74a-fa775beb4f15)


![Accuracy and Loss](https://github.com/user-attachments/assets/8cc6d2ed-0727-4ec4-a573-df26a8dd430c)


![Training Class Distribution (Before and After SMOTE)](https://github.com/user-attachments/assets/56971d44-6453-4ac9-9e22-f2694c3d80b7)
