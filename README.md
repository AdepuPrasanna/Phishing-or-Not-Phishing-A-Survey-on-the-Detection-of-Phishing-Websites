# Phishing-or-Not-Phishing: A Survey on the Detection of Phishing Websites

**A comprehensive study and implementation focused on identifying phishing websites using dataset analysis and machine learning techniques.**

## 🧠 Overview

Phishing is a major cybersecurity threat where attackers deceive users by creating fake websites resembling legitimate ones to steal sensitive information like credentials, financial data, etc. Detecting phishing websites effectively is crucial to protect user data and maintain trust online. This project presents a _survey of phishing detection techniques_, combined with a practical implementation that demonstrates how machine learning models can be used to classify URLs/websites as phishing or legitimate. :contentReference[oaicite:0]{index=0}

## 📁 Repository Structure

Phishing-or-Not-Phishing-A-Survey-on-the-Detection-of-Phishing-Websites/
├── .ipynb_checkpoints/
├── pycache/
├── static/
├── templates/
├── app.py # Main web app to detect phishing
├── Notebook.ipynb # EDA + ML training notebook
├── legitimate.csv # Legitimate URL dataset
├── phishing.csv # Phishing URL dataset
├── online-valid.csv # Online validation dataset
├── model.sav # Saved classification model
├── testcases.txt
├── requirements.txt # Python dependencies
├── signup.db # Sample database
├── Final Result.png # Example output screenshot
└── Curlie.csv # Feature / URL source file

## 📌 Key Features

✔️ Integrated survey of state-of-the-art phishing detection techniques, including:

- List-based methods
- Similarity-based approaches
- Machine learning and feature-based classification strategies :contentReference[oaicite:1]{index=1}

✔️ Machine learning model to detect phishing websites  
✔ Web app (`app.py`) for real-time phishing classification  
✔ Notebook for EDA and model building  
✔ Datasets containing labeled phishing and legitimate URLs

## 🛠 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AdepuPrasanna/Phishing-or-Not-Phishing-A-Survey-on-the-Detection-of-Phishing-Websites.git
   cd Phishing-or-Not-Phishing-A-Survey-on-the-Detection-of-Phishing-Websites
   ```

2.Create & activate a virtual environment (optional but recommended)

python3 -m venv venv
source venv/bin/activate # macOS/Linux

# venv\Scripts\activate # Windows

3.Install dependencies

pip install -r requirements.txt

🚀 Usage
🧪 Run Survey Notebook

Open the Jupyter Notebook for exploratory data analysis and training:

jupyter notebook Notebook.ipynb

🖥️ Launch Web App
python app.py

Visit http://localhost:5000 in your browser.

Enter a URL to check whether it's phishing or not based on the loaded model.

📊 Datasets

This project includes three CSV files:

File Description
phishing.csv Labeled phishing URLs
legitimate.csv Labeled legitimate URLs
online-valid.csv Dataset for validation

You can update these datasets with new or larger sources such as PhishTank or other public repositories.

🧪 Model

The classification model is stored in model.sav.

It’s trained to distinguish phishing and legitimate website URLs based on extracted features.

📝 References

This project is built upon research and techniques discussed in academic surveys and publications about phishing detection and classification.
ResearchGate

📌 Contributing

Contributions are welcome! You can improve datasets, test additional classification methods (e.g., deep learning), or enhance the web app.
