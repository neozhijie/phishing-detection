# README: Data Mining Models

This repository contains Python files implementing various machine learning and data mining models for phishing detection. The models are categorized into:

- Individual traditional machine learning methods
- Individual deep learning methods
- Traditional ensemble models
- Deep learning ensemble models
- Hybrid ensemble models (combining traditional and deep learning approaches)

---

## File Structure

### **EDA and Preprocessing**
1. **`1_Phishing (Processing and Feature Selection).ipynb`**  


### **Individual Traditional Methods**
1. **`2_Phishing-Ensemble-Traditional-Individual-COMPILED.ipynb`**  

### **Traditional Ensemble Models**
1. **`3_Phishing-Ensemble-Traditional-Bagging.ipynb`**  
2. **`4_Phishing-Adaboost Traditional.ipynb`**
3. **`5_Phishing-Individual Model-Xgboost Traditional.ipynb`**
4. **`6_Phishing-Custom Boosting.ipynb`**


### **Individual Deep Learning Methods**
1. **`7_Phishing-MLP.ipynb`**  
2. **`8_Phishing-CNN.ipynb`**  
3. **`9_Phishing-LSTM.ipynb`**  


### **Deep Learning Ensemble Models**
1. **`10_Phishing-Ensemble-Stacking-3-Deep-Learning.ipynb`**  
2. **`11_Phishing-Ensemble-Hard-Voting-3-Deep-Learning.ipynb`**  


### **Hybrid Ensemble Model**
1. **`12_Phishing-Ensemble-Deep-and-Trad Ensemble_all.ipynb`**  


## Dependencies
Ensure the following Python packages are installed before running any scripts:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `imbalanced-learn`  
- `tensorflow`
- `keras`  
- `keras-tuner`  
- `scikeras`  
- `xgboost`

## Installation
Use the following command to install all dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn tensorflow keras keras-tuner scikeras xgboost
```

OR

```bash
pip install -r requirements.txt
```

## Performance Evaluation
Each model script includes the following evaluation metrics: Accuracy, Precision, Recall, f1 score
