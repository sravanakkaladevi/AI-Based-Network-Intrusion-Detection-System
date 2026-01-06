---
title: AI-Based-Network-Intrusion-Detection-System
emoji: 🛡️
colorFrom: blue
colorTo: green
sdk: streamlit
sdk_version: 1.39.0
app_file: app.py
pinned: false
---

# 🛡️ AI-Based Network Intrusion Detection System (Student Project)

This project demonstrates how to use **Machine Learning (Random Forest)** and **Generative AI (Grok)** to detect and explain network attacks (specifically DDoS).

## 🚀 How to Use
1. **Enter API Key:** Paste your Grok API key in the sidebar (optional, for AI explanations).
2. **Train Model:** Click the "Train AI Model" button. The system loads the `Friday-WorkingHours...` dataset automatically.
3. **Simulate:** Click "Simulate Random Packet" to pick a real network packet from the test set.
4. **Analyze:** See if the model flags it as **BENIGN** or **DDoS**, and ask Grok to explain why.

## 📂 Files
- `app.py`: The main Python application code.
- `requirements.txt`: List of libraries used.
- `Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv`: The dataset (CIC-IDS2017 subset).

## 🎓 About
Created for a university cybersecurity project to demonstrate the integration of traditional ML and LLMs in security operations."# AI-Based-Network-Intrusion-Detection-System" 
# Vodafone Virtual Internship – AI-Based Network Intrusion Detection System

This project demonstrates an **AI-Based Network Intrusion Detection System (NIDS)**
using the **CIC-IDS2017 dataset** and **Random Forest algorithm**.

## Features

- Real-world CIC-IDS2017 dataset (DDoS traffic)
- Data cleaning (NaN, infinity, extreme values handled)
- Random Forest classification
- Performance metrics (Accuracy, Confusion Matrix, Classification Report)
- Interactive Streamlit dashboard
- Live traffic analysis

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Matplotlib, Seaborn

## How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Dataset

CIC-IDS2017 dataset
(Dataset not uploaded due to size limits)

## Dataset Information

This project uses the **CIC-IDS2017 (Canadian Institute for Cybersecurity)** dataset.

Due to the large size of the dataset files, they are **not included in this GitHub repository**.

### Official Dataset Source

🔗 https://www.unb.ca/cic/datasets/ids-2017.html

### Dataset Used in This Project

- **Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv**
- Traffic Type: Benign + DDoS attacks

### How to Use the Dataset

1. Download the dataset from the official CIC website
2. Extract the CSV files
3. Place the required file inside the project directory:
4. Run the application using:

```bash
streamlit run app.py

### Output

Accuracy ~99.9%

Low false positives and false negatives
## Author

AKKALADEVI.SRAVAN KUMAR
```
