# Anomaly-Detection-In-Network-Traffic
This code focuses on building a machine learning pipeline for anomaly detection, with key steps such as data preprocessing, class imbalance handling, feature engineering, and model training. It begins by handling missing values and encoding categorical features, followed by generating new statistical features. The dataset is scaled using MinMaxScaler for normalization. Class imbalance is addressed using RandomUnderSampler and SMOTE for generating synthetic data. Random Forest and SVM models are trained and evaluated using accuracy, precision, recall, and ROC-AUC metrics. Visualizations like confusion matrices and ROC curves provide insights into model performance and anomaly detection.

Key Points:
- Library Installation*: Libraries for data processing (pandas, numpy), machine learning (scikit-learn), deep learning (tensorflow), and explainable AI (shap, lime) are installed.
- Data Preprocessing*: Handles missing values, encodes categorical columns, and generates additional features like packet_mean, packet_std, and packet_sum.
- Feature Scaling*: Normalizes features using MinMaxScaler.
- Class Imbalance Handling*: Uses RandomUnderSampler and SMOTE to address class imbalance.
- Model Training*: Models like Random Forest and SVM are trained, and their performance is evaluated using metrics like accuracy, precision, recall, and ROC-AUC.
- Anomaly Detection*: Implements anomaly detection and visualizations using confusion matrices and ROC curves.
