# 📞 DTMF – Dual Tone Multi-Frequency Generator & Decoder

This project implements a full pipeline to generate and decode DTMF (Dual-Tone Multi-Frequency) signals — commonly used in telephone keypads.

## 🔧 Features

- ✅ Generate audio tones for keypad symbols (0–9, *, #, A–D)
- ✅ Decode DTMF signals using frequency analysis (FFT)
- ✅ Spectrogram visualization with `matplotlib`
- ✅ Frequency definitions based on DTMF standard
- ✅ Clean modular implementation in Python

## 🛠️ Technologies

- Python
- NumPy
- Librosa
- Matplotlib
- Einops

## 📸 Example

Visual output of tone detection and spectrogram display:
*(Add a screenshot if you want)*

## ▶️ How to Run

1. Install required packages:
    ```bash
   pip install numpy matplotlib librosa einops
   
2. Launch the Jupyter notebook:
   ```bash
   jupyter notebook DTMF.ipynb
