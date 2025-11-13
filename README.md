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

## Setup
This project requires Python 3.10.0 or later with the necessary dependencies installed.

To install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running Notebooks
Launch Jupyter Notebook and open any of the included notebooks to explore the experiments.

```bash
jupyter notebook
```

### Running the Streamlit App
To run the Streamlit dashboard for real-time detection:

```bash
streamlit run app/main.py
```

## Progress

### Before midsem
- `cnn-model.ipynb`: Convolutional Neural Network based model experiments for audio classification.
- `Hubert.ipynb`: Experiments using the HuBERT model for self-supervised learning on audio features.
- `LSTM.ipynb`: Long Short-Term Memory network based experiments for sequential audio data processing.
- `resnet.ipynb`: ResNet architecture experiments for deep residual learning on spectrograms.
- `wavenet.ipynb`: WaveNet model experiments for generative modeling of audio waveforms.
- `wavlm-1.ipynb`: Experiments using the WavLM model for large-scale self-supervised speech representation learning.

### After midsem
- Developed a **Streamlit dashboard** for real-time demo and visualization.
- Upload FLAC audio files for analysis
- Record audio on-the-spot for real-time detection
- Prediction functionality to classify audio as spoofed or bonafide
- Visualizations including waveform, MFCC (Mel-Frequency Cepstral Coefficients), and spectrogram displays

## Team Members
- 22bds066 - Yashraj Kadam - BiLSTM model experiments, Streamlit dashboard development
- 22bds043 - Parishri Shah - Hubert model experiments, audio visualizations (waveform, MFCC, spectrogram) 
- 22bds045 - Preethi Varshala S - ResNet model experiments, audio recording functionality
- 22bec052 - Rohit Thakur - WavLM model experiments, FLAC file upload and prediction features
