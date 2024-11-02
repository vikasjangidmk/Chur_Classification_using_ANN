# 🎯 Churn Classification Using ANN

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Python](https://img.shields.io/badge/python-3.10+-blue.svg) ![Status](https://img.shields.io/badge/status-active-brightgreen.svg)

## Overview
This project leverages an Artificial Neural Network (ANN) to predict customer churn, helping identify customers likely to discontinue a service. By understanding these patterns, businesses can implement proactive retention strategies.

## 📑 Table of Contents
- [🔧 Installation](#-installation)
- [📂 Project Structure](#-project-structure)
- [🚀 Steps to Run](#-steps-to-run)
- [📊 Experiments](#-experiments)
- [🔍 Prediction](#-prediction)
- [📱 Streamlit App](#-streamlit-app)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

## 🔧 Installation

To set up this project, follow these instructions:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vikasjangidmk/Chur_Classification_using_ANN.git
   cd Churn-Rate-Classification-ANN

2. **Create a virtual environment:**
conda create -p venv python=3.10

3. **Activate the virtual environment:**
conda activate venv/

4. **Install the required packages:**
pip install -r requirements.txt

5. **Install the IPython kernel:**
pip install ipykernel

**📂 Project Structure**
The following outlines the project files and directories:

plaintext
Copy code
├── data                    # Datasets for training and testing
├── notebooks               # Jupyter notebooks for EDA, experimentation, and prediction
│   ├── experiments.ipynb   # Notebook for experimenting with models and configurations
│   └── prediction.ipynb    # Notebook focused on generating predictions
├── src                     # Source code for model training, data processing, etc.
├── app.py                  # Streamlit application for model deployment
├── requirements.txt        # List of dependencies
└── README.md               # Project overview and setup instructions

**🚀 Steps to Run**
1. Complete experiments.ipynb: Perform model experimentation, tuning, and evaluation.

2. Complete prediction.ipynb: Run the prediction notebook to evaluate the trained model on unseen data.

3. Build app.py using Streamlit: Use Streamlit to create an interactive app for churn prediction.

4. Deploy on Streamlit: Deploy the app on Streamlit to share predictions interactively.

**📊 Experiments**
The experiments.ipynb notebook contains steps for training and optimizing the ANN model. It provides insights into model performance on the training and validation datasets and includes techniques used to improve accuracy and minimize error rates.

**🔍 Prediction**
The prediction.ipynb notebook is used to generate predictions with the final trained model. This notebook demonstrates the model’s performance on test data and provides detailed output and metrics.

**📱 Streamlit App**
The app is designed to offer users an interactive experience for customer churn prediction. Through Streamlit, you can upload customer data and receive real-time predictions on churn probability.

**To run the app locally:**
streamlit run app.py

**🤝 Contributing**
We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to your branch (git push origin feature-branch).
5. Submit a pull request.

**📜 License**
This project is licensed under the MIT License - see the LICENSE file for details.