# ELAForgeNet: A Hybrid CNN-LSTM Framework for Robust ImageForgery Detection

ELAForgeNet is a deep learning-based framework designed to detect image forgeries (splicing and copy-move alterations) using a hybrid approach. The model utilizes **Error Level Analysis (ELA)** to highlight inconsistencies in JPEG compression rates, feeds those artifacts into a **Convolutional Neural Network (CNN)** for spatial feature extraction, and leverages a **Long Short-Term Memory (LSTM)** network to analyze sequential pixel dependencies for robust forgery localization.

---

## 🚀 Key Features
* **Error Level Analysis (ELA) Preprocessing:** Automatically detects compression anomalies common in tampered images.
* **Hybrid CNN-LSTM Architecture:** Combines powerful spatial feature extraction with sequential context processing.
* **Trained on CASIA2:** Optimized and validated using the widely acknowledged CASIA V2.0 dataset.

---

## 📁 Repository Structure
```text
├── CASIA2/                  # Image forgery dataset (Local only, not tracked by Git)
├── venv/                    # Python virtual environment (Local only)
├── code.ipynb               # Data preprocessing and exploratory data analysis
├── code2.ipynb              # Model architecture, training pipeline, and evaluation
├── .gitignore               # Ensures large datasets/weights are not pushed to GitHub
└── README.md                # Project documentation
