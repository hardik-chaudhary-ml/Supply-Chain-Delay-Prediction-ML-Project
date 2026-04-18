# 🚀 Supply Chain Delay Prediction using Machine Learning

> Predicting late deliveries using ML models like Logistic Regression, Decision Tree, and Random Forest.



📌 Project Overview



This project focuses on predicting delivery delays in supply chain operations using Machine Learning techniques.

The goal is to help businesses identify potential delays in advance and improve logistics efficiency.



\---



🎯 Objectives



\- Predict whether an order will be delayed or not

\- Analyze key factors affecting delivery time

\- Build and optimize a Random Forest model

\- Evaluate model performance using multiple metrics



\---



📊 Dataset



\- Dataset used: DataCo Supply Chain Dataset

\- Size: \~90MB (not included in this repository)



📥 Download Dataset from Google Drive:

👉 https://drive.google.com/file/d/1HVDbNte-123z50nk-dpi7PbQ-UF6pqms/view?usp=drivesdk



⚠️ After downloading, place the dataset in:



data/DataCoSupplyDataset.csv



\---



📁 Project Structure



Supply-Chain-Delay-Prediction-ML/

│

├── supply\_chain\_delay\_analysis.ipynb   # Main notebook

├── README.md                          # Project documentation

├── requirements.txt                   # Dependencies

│

└── data/

&#x20;   └── description.csv                # Dataset description (data dictionary)



\---



🛠️ Technologies Used



\- Python 🐍

\- Pandas \& NumPy

\- Matplotlib \& Seaborn

\- Scikit-learn



\---

## 📊 Results

- Random Forest achieved highest accuracy
- Model evaluated using Precision, Recall, F1-score, ROC-AUC
- Class imbalance handled using SMOTE

\---

⚙️ Model Used



\- Random Forest Classifier

\- Hyperparameter tuning using:

&#x20; - GridSearchCV

&#x20; - RandomizedSearchCV



\---



📈 Model Performance



Metric| Score

Accuracy| 0.74

Precision| 0.83

Recall| 0.68

AUC Score| 0.82



\---



📊 Visualizations



\- Feature Importance

\- Confusion Matrix

\- ROC Curve (AUC = 0.82)



\---



🚀 How to Run



1️⃣ Clone Repository



git clone https://github.com/hardik-chaudhary-ml/Supply-Chain-Delay-Prediction-ML-Project.git
upply-Chain-Delay-Prediction-ML-Project



2️⃣ Install Requirements



pip install -r requirements.txt



3️⃣ Add Dataset



\- Download dataset from Drive

\- Place it inside "data/" folder



4️⃣ Run Notebook



jupyter notebook



\---



💡 Key Insights



\- Order Hour and Shipping Days are major factors

\- Shipping mode significantly impacts delays

\- Certain regions show higher delay probability



\---



📌 Future Improvements



\- Try advanced models (XGBoost, LightGBM)

\- Deploy model using Flask/Streamlit

\- Add real-time prediction system



\---



\## 👨‍💻 Author



\*\*Hardik Chaudhary\*\*

B.Tech CSE | Aspiring Data Analyst / Data Scientist



📧 Email: \[hardik1chaudhary@gmail.com](mailto:hardik1chaudhary@gmail.com)



