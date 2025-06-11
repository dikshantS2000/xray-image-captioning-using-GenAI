# Xray-Image-Report-Generation-Using-GenAI
This repository contains two deep learning models:

1. X-ray Report Generator – Automatically generates diagnostic captions from chest X-ray images using a CNN + RNN architecture.
2. Fracture Classifier – Classifies X-ray images for fracture detection using a CNN-based model.

📂 Dataset Sources

X-ray Report Generator: Dataset sourced from MIMIC-CXR or similar public datasets with X-ray images and corresponding radiology reports.
Fracture Classifier: Based on curated datasets from platforms like Kaggle focused on bone X-rays and fracture classification tasks.

🧰 Implementation Highlights

X-ray Report Generator (xray_report_gen.ipynb):

CNN: Feature extraction from X-ray images.
RNN (LSTM/GRU): Generates medical reports from image features.
Preprocessing: Image resizing, normalization, and tokenizer for text.
Output: Radiology report predictions in natural language.

Fracture Classifier (Frac_classify.ipynb):

CNN Architecture: Custom layers for feature extraction and classification.
Preprocessing: Image augmentation and normalization.
Output: Predicts fracture vs. non-fracture class labels.

🚀 Getting Started
1. Clone the repo
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
2. Install requirements
```
pip install -r requirements.txt
```
3. Run the notebooks in Jupyter or Colab.
