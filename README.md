# 🎯 Customer Status Prediction ML Project

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<div align="center">

**🚀 A comprehensive machine learning project that predicts customer status using advanced data science techniques**

![Customer Prediction](https://img.shields.io/badge/Accuracy-52%25-brightgreen?style=for-the-badge)
![Models](https://img.shields.io/badge/ML_Models-8-blue?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Records-505-orange?style=for-the-badge)

</div>

## 📋 Project Overview

This project implements a comprehensive **supervised learning pipeline** to predict customer status using multiple machine learning algorithms. The analysis includes data preprocessing, model training, hyperparameter optimization, ensemble methods, and thorough evaluation.

### 🎯 Key Results
- **Best Model**: Decision Tree (Tuned) 
- **Accuracy**: 52.00%
- **Dataset**: 505 customer records
- **Models Evaluated**: 8 different algorithms
- **Target Classes**: Active, At Risk, Churned

## 📊 Dataset Information

- **Size**: 505 customer records
- **Features**: 7 predictive features (Gender, Age, Country, Subscription Type, Purchase Amount, Payment Method, Feedback Score)
- **Target Variable**: Customer Status (Active, At Risk, Churned)
- **Missing Values**: 263 handled appropriately
- **Data Quality**: 99.0% retention after cleaning

## 🔬 Methodology

### Data Preprocessing
- ✅ Missing value imputation (median for numeric, mode for categorical)
- ✅ Duplicate removal
- ✅ Feature encoding (Label Encoding)
- ✅ Feature scaling (StandardScaler)
- ✅ Stratified train-test split (80%/20%)

### Machine Learning Pipeline
- **Base Models**: Logistic Regression, Decision Tree, Random Forest, SVM, KNN
- **Optimization**: Hyperparameter tuning with GridSearchCV/RandomizedSearchCV
- **Ensemble Methods**: Bagging, AdaBoost, Stacking
- **Validation**: 5-fold cross-validation

## 📈 Results Summary

| Rank | Model | Type | Accuracy | Precision | Recall | F1-Score |
|------|-------|------|----------|-----------|--------|----------|
| 1 | Decision Tree | Tuned | 0.5200 | 0.5222 | 0.5200 | 0.4236 |
| 2 | AdaBoost | Ensemble | 0.5200 | 0.5111 | 0.5200 | 0.4651 |
| 3 | Random Forest | Tuned | 0.5100 | 0.5185 | 0.5100 | 0.4427 |
| 4 | KNN | Tuned | 0.5100 | 0.5037 | 0.5100 | 0.4444 |
| 5 | Stacking | Ensemble | 0.5000 | 0.5000 | 0.5000 | 0.4444 |

## 🛠️ Installation & Usage

### Prerequisites
```bash
Python 3.8+
pip install -r requirements.txt
```

### Required Libraries
```python
pandas >= 1.3.0
numpy >= 1.21.0
scikit-learn >= 1.0.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
python-pptx >= 0.6.21
```

### Running the Project
1. Clone the repository
```bash
git clone https://github.com/yourusername/customer-status-prediction.git
cd customer-status-prediction
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook
```bash
jupyter notebook final_ml_lab.ipynb
```

## 📁 Project Structure

```
├── final_ml_lab.ipynb                 # Main Jupyter notebook
├── dataset.csv                        # Customer dataset
├── detailed_model_results.csv         # Complete model comparison
├── project_summary_report.csv         # Executive summary
├── best_model_predictions.csv         # Best model predictions
├── ML_Customer_Status_Prediction_Presentation.pptx  # PowerPoint presentation
├── README.md                          # This file
├── requirements.txt                   # Python dependencies
└── LICENSE                           # MIT License
```

## 🔍 Key Features

- **Comprehensive Analysis**: 8 different ML algorithms evaluated
- **Professional Reporting**: Detailed analysis with visualizations
- **Production Ready**: Scalable solution with proper validation
- **Documentation**: Complete technical documentation
- **Presentation**: Professional PowerPoint presentation included

## 📊 Visualizations

The project includes:
- 📈 Model performance comparison charts
- 🔥 Confusion matrices for top models
- 📊 Feature distribution analysis
- 🎯 Results summary dashboards

## 🎯 Business Impact

- **Customer Segmentation**: Identify at-risk customers
- **Retention Strategy**: Proactive customer management
- **Revenue Protection**: Prevent customer churn
- **Scalable Solution**: Ready for production deployment

## 🚀 Future Enhancements

- [ ] Deep learning approaches (Neural Networks)
- [ ] Feature engineering optimization
- [ ] Real-time prediction API
- [ ] Model interpretability (SHAP/LIME)
- [ ] Advanced ensemble methods

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub:https://github.com/imondol41
- LinkedIn: https://linkedin.com/in/ibrahim-kholilulla-32230431a
- Email:imondol41@gmail.com

## 🙏 Acknowledgments

- Dataset source: Customer relationship management data
- Inspiration: Modern machine learning best practices
- Tools: Scikit-learn, Pandas, Matplotlib ecosystem

---

⭐ **If you found this project helpful, please give it a star!** ⭐
