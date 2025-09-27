# Customer Churn Prediction and Sales Dashboard

## 📊 Project Overview

This project leverages **Data Analytics and Machine Learning** to analyze customer behavior and predict churn probability. The system is essential for businesses, e-commerce platforms, and service providers to enhance customer retention strategies through data-driven insights.

## 🚀 Key Features

### 1. Data Acquisition & Preprocessing
- **ETL Operations**: Extract, Transform, Load from multiple data sources
- **Missing Value Handling**: Comprehensive NaN value treatment
- **Data Normalization**: Standard scaling of numerical features
- **Categorical Encoding**: Label encoding for categorical variables
- **Feature Engineering**: Engagement scores, payment behavior, customer value metrics

### 2. Churn Prediction Models
#### Supervised Learning:
- **Logistic Regression** with hyperparameter tuning
- **XGBoost** Gradient Boosting
- **LightGBM** for efficient training
- **Random Forest** for robust classification

#### Deep Learning:
- **Artificial Neural Networks (ANNs)** with 20 epochs
- **Recurrent Neural Networks (RNNs)** for time-based pattern recognition

#### Unsupervised Learning:
- **K-Means Clustering** for customer segmentation
- **DBSCAN** for anomaly detection in customer behavior

### 3. Interactive Insights
- Real-time customer retention analysis
- Customer segmentation for targeted marketing
- Anomaly detection for proactive intervention

## 🛠 Technology Stack

### Data Processing & ML Models
- **Python**, Pandas, NumPy, Scikit-learn
- **XGBoost**, LightGBM for gradient boosting
- **TensorFlow/Keras** for deep learning
- **K-Means & DBSCAN** for customer segmentation

### Key Libraries
```python
pandas, numpy, scikit-learn, xgboost, lightgbm
tensorflow, keras, matplotlib, seaborn
```

## 📁 Project Structure

```
customer-churn-prediction/
│
├── main.ipynb                 # Main Jupyter notebook with complete pipeline
├── customer_churn_dataset-training-master.csv    # Training dataset
├── customer_churn_dataset-testing-master.csv     # Testing dataset
└── README.md                  # This file
```

## 🏗 Implementation Steps

### Step 1: Environment Setup
- Install required libraries and dependencies
- Import necessary packages for data processing and ML

### Step 2: Data Acquisition & ETL
- Load and merge training/testing datasets
- Handle file path exceptions with sample data generation

### Step 3: Data Preprocessing
- Identify and handle missing values (NaN)
- Median imputation for numerical features
- Mode imputation for categorical variables

### Step 4: Feature Engineering
- Create engagement scores from usage patterns
- Calculate payment behavior metrics
- Generate customer value scores
- Encode categorical variables

### Step 5: Data Preparation
- Standardize numerical features
- Split data into 80% training and 20% testing sets
- Ensure stratified sampling for balanced classes

### Step 6: Supervised Learning
- Hyperparameter tuning using GridSearchCV
- Multiple algorithm comparison:
  - Logistic Regression
  - XGBoost
  - LightGBM
  - Random Forest

### Step 7: Deep Learning
- ANN architecture with dropout regularization
- RNN implementation for sequential patterns
- 20-epoch training for efficiency

### Step 8: Unsupervised Learning
- Customer segmentation using K-Means
- Anomaly detection with DBSCAN
- Cluster analysis for business insights

### Step 9: Model Evaluation
- Comprehensive performance comparison
- Accuracy metrics and feature importance
- Best model selection

## 📊 Model Performance Metrics

The project evaluates models based on:
- **Accuracy**: Overall prediction correctness
- **Feature Importance**: Key drivers of churn
- **Cluster Analysis**: Customer segment insights
- **Anomaly Detection**: Identifying unusual patterns

## 🎯 Business Applications

1. **Customer Retention**: Identify at-risk customers proactively
2. **Targeted Marketing**: Segment customers for personalized campaigns
3. **Resource Optimization**: Focus retention efforts on high-value segments
4. **Product Development**: Understand feature usage patterns

## ⚡ Quick Start

1. **Upload datasets** to your Google Colab environment
2. **Run main.ipynb** sequentially cell by cell
3. **Monitor progress** through validation metrics
4. **Analyze results** from model comparisons and feature importance

## 📈 Expected Outcomes

- **Churn Prediction Accuracy**: >85% with optimized models
- **Customer Segments**: 3-5 distinct behavioral clusters
- **Key Insights**: Identified drivers of customer retention
- **Actionable Recommendations**: Data-driven strategies for reducing churn

## 🔧 Customization Options

- Adjust hyperparameters in GridSearchCV for specific use cases
- Modify neural network architecture for complex patterns
- Add new features based on domain knowledge
- Extend with real-time data streaming capabilities

## 📞 Support

For questions or issues regarding this implementation, refer to the code comments in `main.ipynb` or consult the scikit-learn and TensorFlow documentation for specific algorithm details.

---

**Note**: This project is designed for educational and business intelligence purposes. Always validate model performance with domain experts before deploying in production environments.
