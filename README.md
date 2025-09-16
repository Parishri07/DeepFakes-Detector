# DeepFakes-Detector

## 📌 Overview
This project focuses on detecting **deepfake (synthetic/spoofed) speech** using deep learning models.  
Currently, the implementation is available in the form of **Jupyter Notebooks** that cover model training, evaluation, and analysis.  

## 📊 Current Progress
- Implemented and tested multiple models:
  - **Wav2Vec2 + Bi-LSTM**
  - **HuBERT**
  - **WavLM**
  - **ResNet101**
- Training and evaluation performed on **ASVspoof 2019 Logical Access (LA) dataset**.
- Models show promising results with **low Equal Error Rate (EER)**, with **WavLM** achieving the best performance.

---

## 🔮 Future Work
- Develop a **Streamlit dashboard** for real-time demo and visualization.

---

## 📚 References
- [ASVspoof 2019 Challenge Dataset](https://www.asvspoof.org)
- Baevski et al., *Wav2Vec2*
- Hsu et al., *HuBERT*
- Chen et al., *WavLM*
- He et al., *ResNet*
