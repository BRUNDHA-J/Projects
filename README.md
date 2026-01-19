## Overview
This project applies Named Entity Recognition (NER) to Air Traffic Control (ATC) transcripts using deep learning models.
The goal is to automatically extract important aviation information from ATC communications.

## Problem
ATC transcripts are noisy, do not strictly follow standard phraseology, and contain transcription errors.
Manual extraction of information is time-consuming and error-prone.

## Dataset
The dataset contains 8,241 ATC command transcripts provided by Honeywell Technology Solutions Pvt. Ltd.
Each command may include multiple entities such as call signs, flight levels, speed, and directions.

## Approach
Text preprocessing and normalization
BIO tagging using rule-based patterns
Sequence labeling using deep learning models
Evaluation using Precision, Recall, and F1-score

## Supervised Models Used
LSTM
Bi-LSTM
GRU
Bi-GRU
BERT
Bi-LSTM with CRF

## Results
BERT and Bi-LSTM with CRF achieved the best performance with near-perfect F1-scores.
Context-aware models performed better than basic recurrent models.

Tech Stack
Python
TensorFlow / Keras
HuggingFace Transformers
NumPy, Pandas, Scikit-learn

# Publication
https://ieeexplore.ieee.org/document/10440794/citations#citations
