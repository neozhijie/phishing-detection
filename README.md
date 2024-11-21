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
1. **`traditional-individual-1.ipynb`**  
2. **`traditional-individual-1.ipynb`**  
3. **`traditional-individual-1.ipynb`**  
4. **`traditional-individual-1.ipynb`**  
5. **`traditional-individual-1.ipynb`**  
6. **`traditional-individual-1.ipynb`**  


### **Traditional Ensemble Models**
1. **`traditional_ensemble_1.py`**  
2. **`traditional_ensemble_2.py`**  


### **Individual Deep Learning Methods**
1. **`14_Phishing-MLP.ipynb`**  
2. **`15_Phishing-CNN.ipynb`**  
3. **`16_Phishing-LSTM.ipynb`**  


### **Deep Learning Ensemble Models**
1. **`18_Phishing-Ensemble-Hard-Voting-3-Deep-Learning.ipynb`**  
2. **`18_Phishing-Ensemble-Hard-Voting-3-Deep-Learning.ipynb`**  


### **Hybrid Ensemble Model**
1. **`19_Phishing-Ensemble-Deep-and-Trad Ensemble_all.ipynb`**  


## Dependencies
Ensure the following Python packages are installed before running any scripts:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `imbalanced-learn`  
- `tensorflow` or `pytorch`  
- `keras`  
- `keras-tuner`  
- `scikeras`  
- `xgboost`

## Installation
Use the following command to install all dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn tensorflow keras keras-tuner scikeras xgboost

## Performance Evaluation
Each model script includes the following evaluation metrics: Accuracy, Precision, Recall, f1 score