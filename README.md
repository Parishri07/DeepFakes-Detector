# DeepFakes-Detector

## Overview
This project focuses on detecting **deepfake (synthetic/spoofed) speech** using deep learning models.  
Currently, the implementation is available in the form of **Jupyter Notebooks** that cover model training, evaluation, and analysis. The notebooks explore various deep learning architectures and feature extraction techniques for detecting spoofed versus bonafide audio samples.

## Dataset
- **Source:** [ASVspoof 2019 Challenge Dataset](https://www.asvspoof.org)  
- **Subset Used:** Logical Access (LA)  
- **Composition:**  
  - Training: 2,580 bonafide + 22,800 spoofed utterances  
  - Development: 1,484 bonafide target, 1,064 bonafide non-target, 22,296 spoofed utterances  
- Spoofed samples are generated using **Text-to-Speech (TTS)** and **Voice Conversion (VC)** algorithms.  
- The dataset provides a challenging benchmark for deepfake speech detection tasks.  

## Notebooks Included
- `cnn-model.ipynb`: Convolutional Neural Network based model experiments.
- `Hubert.ipynb`: Experiments using the HuBERT model.
- `LSTM.ipynb`: Long Short-Term Memory network based experiments.
- `resnet.ipynb`: ResNet architecture experiments.
- `wavenet.ipynb`: WaveNet model experiments.
- `wavlm-1.ipynb`: Experiments using the WavLM model.

## Setup
This project requires Python 3.10.0 or later with the necessary dependencies installed.

To install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Launch Jupyter Notebook and open any of the included notebooks to explore the experiments.

```bash
jupyter notebook
```

## Future Work
- Develop a **Streamlit dashboard** for real-time demo and visualization.
- Upload FLAC audio files for analysis
- Record audio on-the-spot for real-time detection
- Prediction functionality to classify audio as spoofed or bonafide
- Visualizations including waveform, MFCC (Mel-Frequency Cepstral Coefficients), and spectrogram displays

## Team Members
- Yashraj Kadam (22bds066)
- Parishri Shah (22bds043)
- Preethi Varshala S (22bds045)
- Rohit Thakur (22bec052)
