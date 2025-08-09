# 🏥 Medical Cost Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![ML](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0+-orange)

A machine learning project predicting medical insurance costs using demographic and health factors.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Findings](#-key-findings)
- [Data Analysis](#-data-analysis)
- [Model Performance](#-model-performance)
- [Installation](#-installation)
- [Usage](#-usage)
- [License](#-license)

## 📋 Project Overview
Predicts medical expenses using:
- **3 Regression Models**: Linear, Decision Tree, Random Forest
- **7 Key Features**: Age, BMI, Smoking Status, Region, etc.
- **Best Model**: Random Forest (R²: 0.863)

## 🔍 Key Findings
![Correlation Analysis](images/1.png)

- Smokers pay **3-4x higher** medical costs
- BMI strongly correlates with charges (r=0.20)
- Age shows moderate correlation (r=0.30)

## 📊 Data Analysis
### Feature Distributions
| Age | BMI | Charges |
|-----|-----|---------|
| ![Age Dist](https://via.placeholder.com/150?text=Age+Plot) | ![BMI Dist](https://via.placeholder.com/150?text=BMI+Plot) | ![Charges Dist](https://via.placeholder.com/150?text=Charges+Plot) |

## 🚀 Model Performance
### Linear Regression
![Linear Regression Results](https://github.com/yourusername/Medical_Cost_Prediction/blob/main/images/3.png?raw=true)
- **R²**: 0.783
- **MAE**: $4186

### Decision Tree
![Decision Tree Results](https://github.com/yourusername/Medical_Cost_Prediction/blob/main/images/4.png?raw=true)
- **R²**: 0.725
- **MAE**: $2990

### Random Forest
![Random Forest Results](https://github.com/yourusername/Medical_Cost_Prediction/blob/main/images/5.png?raw=true)
- **R²**: 0.863
- **MAE**: $2524

## 💻 Installation
```bash
git clone https://github.com/yourusername/Medical_Cost_Prediction.git
cd Medical_Cost_Prediction
pip install -r requirements.txt
