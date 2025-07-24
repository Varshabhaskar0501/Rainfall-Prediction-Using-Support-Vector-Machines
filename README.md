# 🌧️ Rainfall Prediction Using Support Vector Machines

A machine learning project to forecast rainfall using historical meteorological data and Support Vector Machines (SVM), aimed at improving agricultural planning, water management, and disaster mitigation.


## 📊 Overview

This project applies **Support Vector Machines (SVM)** to predict rainfall based on daily weather features such as temperature, humidity, wind speed, and more. The model is trained on historical data and achieves over **90.52% accuracy**, outperforming traditional statistical methods.


## 🌐 Dataset

- **Source**: Kaggle  
- **Records**: 73,100 daily weather entries (2024–2025)  
- **Features**: Date, Location, Temperature, Humidity, Wind Speed, Pressure, Cloud Cover, Precipitation  
- **Target**: Binary classification — Will it rain tomorrow? (`RainTomorrow`)


## 🧠 Tools & Libraries

- **Language**: Python  
- **Libraries**: `pandas`, `scikit-learn`, `LabelEncoder`  
- **Algorithms**: SVM with Linear Kernel  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score


## 🔧 Methodology

1. **Data Preprocessing**:
   - Missing value handling
   - Encoding categorical features (Date, Location)
   - Splitting data: 70% train, 15% validation, 15% test

2. **Model Training**:
   - Applied SVM with linear kernel for binary classification
   - Hyperparameter tuning for regularization and kernel options

3. **Evaluation**:
   - **Accuracy**: 90.52%
   - **Precision**: 90.25%
   - **Recall**: 90.52%
   - **F1-Score**: 90.18%


## ✅ Results

The SVM model proved to be highly effective in classifying rainfall occurrences with a balanced trade-off between precision and recall, making it suitable for real-world applications in weather-sensitive sectors.


## 🚀 Future Enhancements

- Explore non-linear kernels (RBF, Polynomial)
- Integrate satellite data and external APIs
- Experiment with hybrid models (e.g., SVM + LSTM)
- Deploy as a real-time prediction service


## 🧾 Conclusion

This study confirms SVM’s power in handling high-dimensional, non-linear meteorological data. The model enhances prediction accuracy and supports climate-responsive decision-making in agriculture and disaster prevention.
