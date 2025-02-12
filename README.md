## **Fraud Detection in Credit Card Transactions**  

### **Goal:**  
To identify anomalous (fraudulent) credit card transactions while minimizing the **False Positive Rate (FPR)** for better fraud detection efficiency.

### **Project Overview:**  
- Worked with a **highly imbalanced dataset** containing **30 PCA-transformed features**, with a fraud-to-non-fraud class ratio of **1000:17**.  
- **Applied supervised classification algorithms** using **stratified random sampling** to ensure balanced training across classes.  
- **Random Forest Classifier** achieved a **Recall score of 0.78** in detecting fraudulent transactions.  
- Improved the **Recall score to 0.82** by training an **Isolation Forest model** in an **unsupervised setting** for anomaly detection.  
- Designed a **Deep Autoencoder Neural Network model**, which achieved the **best Recall score of 0.85** while maintaining a **6.5% False Positive Rate** on fraudulent transactions.

### **Key Technologies & Tools:**  
✅ Python (Pandas, NumPy, Scikit-learn, TensorFlow, Keras)  
✅ Machine Learning: Random Forest, Isolation Forest, Autoencoders  
✅ Data Preprocessing: PCA, Stratified Sampling  
✅ Model Evaluation: Recall, Precision, F1-score, ROC-AUC  

### **Impact & Insights:**  
- **Reduced False Positives** to ensure legitimate transactions are not wrongly flagged.  
- **Improved fraud detection accuracy**, increasing security for financial institutions.  
- Showcased the **effectiveness of deep learning models** like autoencoders in financial anomaly detection.  

