# ⚡ Power System Fault Detection & Classification using IBM Watsonx.ai

This project implements an automated machine learning pipeline for detecting and classifying power system faults using IBM Watsonx.ai. The system utilizes historical sensor data to train models that can accurately predict the type of fault occurring in a power grid, enabling smarter monitoring and faster responses.

## 🚀 Problem Statement
Power system faults can cause severe disruption if not identified quickly. Accurate classification of faults is crucial for real-time corrective actions. This project aims to build a model that can predict fault types based on time-series sensor data.

## 🧠 Proposed Solution
We used **AutoAI** from IBM Watsonx.ai to automate model training and evaluation. The pipeline:
- Loads historical fault data
- Preprocesses and cleans the dataset
- Uses AutoAI to test various models
- Selects the best-performing model for deployment

The best-performing model turned out to be a **Random Forest Classifier** with high classification accuracy.

## 📊 Dataset
- Source: [Kaggle Power System Fault Dataset](https://www.kaggle.com/datasets)
- Features include voltage, current, frequency, and phase details across time.
- Target: Fault type (e.g., LG, LL, LLG, LLLG)

## 🛠️ Technologies Used
- IBM Watsonx.ai Studio
- AutoAI
- Python (Jupyter Notebooks)
- Pandas, Seaborn, Matplotlib
- Scikit-learn

## 📈 Results
- Best Model: Random Forest Classifier
- Accuracy: ✅ High fault detection accuracy
- Evaluation Metrics: Confusion Matrix, Precision, Recall

## 🔮 Future Scope
- Integrate real-time sensor streams for live fault detection
- Deploy model using IBM Cloud Functions or Flask API
- Add fault localization for better grid management

## 📚 References
- IBM Cloud Docs: https://cloud.ibm.com/docs
- Scikit-learn: https://scikit-learn.org
- Kaggle Dataset

## 📁 Folder Structure
```arduino
/power-fault-detection-ibm-watsonx
│
├── notebooks/
│ └── fault_detection.ipynb
├── data/
│ └── power_faults.csv
├── README.md
└── requirements.txt
```


## 👥 Authors
- Adarsh Prasad
- Institution: IEM KOLKATA

