## Consumer-Complaint-Classification-using-LSTM

    This project uses **Natural Language Processing (NLP)** and **Deep Learning (LSTM)** to classify consumer complaints into product categories such as *credit reporting, debt collection, mortgages*, etc. The dataset comes from consumer grievance data.

## 📌 Project Overview
    - **Objective**: Predict the `Product` category from complaint text.  
    - **Data**: Combined fields such as:
    - `Issue`
    - `Sub-issue`
    - `Consumer complaint narrative`
    - `Company`  
    - **Model**: LSTM neural network built with TensorFlow/Keras.  
    - **Output**: 21-class classification with ~94% accuracy.  

## ⚙️ Tech Stack
    - **Python 3.9+**
    - **Pandas, Numpy** → Data cleaning  
    - **Scikit-learn** → Label encoding, metrics  
    - **TensorFlow / Keras** → Deep learning (Embedding, LSTM, Dropout, Dense)  

## 📂 Dataset
    - The dataset file is **not included** in this repository due to size.  
    - If you need the dataset (CSV), please contact me at 📧 **syamaism@gmail.com**.  
    - Expected file: `greviance.csv`  
    - The final model (Grievence.ipynb) is uploaded with the Project.

## 🚀 Usage
    - Open the Jupyter notebook.
    - Upload the given Grievence.ipynb file (for the csv file, contact details given)

## 📊 Results
    -Overall Accuracy: ~94%
    -Macro Avg F1-score: 0.76
    -Weighted Avg F1-score: 0.93
            The model works very well on common complaint categories, but rare categories suffer due to class imbalance.

## 🔮 Future Enhancements
    -Use class weights to handle imbalanced classes
    -Try oversampling/SMOTE for minority complaints
    -Experiment with Bi-LSTM/GRU models
    -Deploy as a web app (Flask/Streamlit)

## 📧 Contact
    👤 Amaljith P 📩 syamaism@gmail.com 🌐 https://www.linkedin.com/in/amaljith-p-b8044b248/
