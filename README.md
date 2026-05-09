# AI-Emotion-Classifier

Speech Emotion Recognition system developed in Python using Machine Learning techniques to classify human emotions from voice recordings.

This project explores the complete ML workflow for audio classification, including preprocessing, feature extraction, model training, and evaluation using emotional speech datasets.

---

## Project Overview

Human voice contains acoustic patterns that can reveal emotional states such as happiness, anger, sadness, or fear.  
The objective of this project is to analyze these patterns and train a machine learning model capable of recognizing emotions from speech audio.

The project was originally developed as a university assignment and later redesigned with a cleaner and more professional structure to serve as a portfolio project.

---

## Features

- Audio preprocessing pipeline
- Feature extraction from speech signals
- MFCC-based acoustic analysis
- Machine Learning emotion classification
- Data visualization and evaluation metrics
- Jupyter Notebook experimentation workflow

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Librosa

---

## Dataset

This project uses a subset of the **CREMA-D (Crowd-sourced Emotional Multimodal Actors Dataset)** dataset for academic and research purposes.

The dataset contains voice recordings labeled with different emotional categories spoken by multiple actors.

Possible emotions include:

- Happy
- Sad
- Angry
- Fear
- Neutral
- Disgust

Dataset reference:

- CREMA-D: https://github.com/CheyneyComputerScience/CREMA-D

---

## Machine Learning Pipeline

```text
Audio Input
    ↓
Preprocessing
    ↓
Feature Extraction (MFCCs)
    ↓
Feature Scaling
    ↓
Model Training
    ↓
Prediction & Evaluation
```

---

## Project Structure

```text
AI-Emotion-Classifier/
│
├── Clasificador_Emociones.ipynb
├── README.md
├── requirements.txt
├── data/
├── models/
└── outputs/
```

---

## Notebook

Main notebook:

👉 [Open Main Notebook](./Clasificador_Emociones.ipynb)

The notebook includes:

- Data loading
- Audio visualization
- Feature extraction
- Model training
- Performance evaluation
- Conclusions and analysis

---

## Results

The model was trained and evaluated using labeled emotional speech data.

Evaluation metrics include:

- Accuracy
- Confusion Matrix
- Classification Report
- Emotion prediction examples

---

## Example Workflow

1. Load audio dataset
2. Extract MFCC features from speech
3. Train classification model
4. Evaluate model performance
5. Predict emotions from unseen audio

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AI-Emotion-Classifier.git
cd AI-Emotion-Classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Deep Learning implementation (CNN / LSTM)
- Real-time microphone emotion detection
- Streamlit web application
- Model optimization and hyperparameter tuning
- Support for additional datasets

---

## License

This project is intended for educational and portfolio purposes.

---

## Author

Developed by [Your Name]

GitHub: https://github.com/your-username
