# 🫀 ECG-Net: Hybrid CNN-BiLSTM for Automated Arrhythmia Classification
### **BioFusion-2025 | University of Sri Jayewardenepura**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![University](https://img.shields.io/badge/University-Sri%20Jayewardenepura-blue)](https://www.sjp.ac.lk/)
[![Competition](https://img.shields.io/badge/Competition-BioFusion--2025-red)](https://science.sjp.ac.lk/)

**ECG-Net by MedX Hackers** is a deep learning-based diagnostic tool designed to automate the detection of cardiac arrhythmias. Developed for the **BioFusion-2025** competition at the **University of Sri Jayewardenepura**, this project aims to make cardiac monitoring faster, more accurate, and accessible.

---

## 🌟 Project Highlights
* **Team:** MedX Hackers
* **Competition:** BioFusion-2025 (USJ)
* **Architecture:** Hybrid 1D CNN + Bidirectional LSTM (BiLSTM)
* **Dataset:** MIT-BIH Arrhythmia (CSV Format)
* **Performance:** ~97%+ Accuracy on unseen test data

---

## 📊 Dataset Information
The model uses the curated MIT-BIH dataset available on Kaggle:
🔗 **[Download Dataset Here](https://www.kaggle.com/datasets/sadmansakib7/ecg-arrhythmia-classification-dataset)**

- **Classes:** Normal (N), Supraventricular (S), Ventricular (V), Fusion (F), and Unclassifiable (Q).
- **Format:** CSV files with 187 signal values and 1 label per row.

---

## 🛠️ Model Architecture
ECG-Net uses a hybrid approach to capture both the shape and the timing of heartbeats:
* **1D CNN Layers:** Extract spatial features and morphology (e.g., QRS complex).
* **BiLSTM Layers:** Map temporal dependencies and rhythm patterns over time.
* **Optimization:** Adam optimizer with categorical cross-entropy loss.

---

## 🤝 Team MedX Hackers
* **Pasindu Harsha** 
* **Navidu Atulugama**
* **Sewmini Samarasinghe**
* **Dinethma Hatharasinghe**
* **Samudra Uduwaka**

---

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---
**Developed with ❤️ by MedX Hackers**
*Empowering heart health through intelligent technology at University of Sri Jayewardenepura.*
