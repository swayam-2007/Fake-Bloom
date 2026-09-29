# Fake News Detector

An AI-powered web application that detects whether a given news article is REAL or FAKE using machine learning. 

## How it Works
The application uses a trained Machine Learning model (such as Passive Aggressive Classifier) trained on TF-IDF features of news articles. 

## Setup Instructions

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the training script (this will create model artifacts in the `models/` directory):
```bash
python src/train.py
```

3. Launch the Streamlit web application:
```bash
streamlit run app.py
```

Or run everything automatically:
```bash
python run_all.py
```
