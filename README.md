AMUF: Attention-Based Multimodal Uncertainty-Aware Fusion for Cardiac Disease Detection
Overview
AMUF is a deep-learning framework designed for robust cardiac disease detection using multimodal ECG and PCG signals. The model incorporates attention-based fusion and uncertainty estimation to improve prediction reliability and enhance clinical interpretability.
•	Multimodal learning: Integrates ECG and PCG signals
•	Attention-based fusion: Adaptive weighting of modality-specific features
•	Uncertainty modeling: Quantifies predictive confidence
•	Modular design: Easily extendable for additional biosignals
•	Complete training and evaluation pipeline

Files Structure
├── models/
├── utils/
├── training/
├── data/
├── AMUF.ipynb

Getting Started
Requirements
Install required libraries with:
pip install torch pandas scikit-learn numpy matplotlib

Usage
Run AMUF training and evaluation via:
python amuf_training.py
