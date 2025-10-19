# Emotion Classification using Transformer Ensemble (RoBERTa + DistilBERT + Meta-Model)

## Overview
This project focuses on emotion classification from text using an **ensemble of transformer-based models**.  
Two pre-trained language models — **RoBERTa** and **DistilBERT** — were fine-tuned individually and then combined through a **meta-classifier** to improve robustness and overall prediction quality.  
The ensemble approach leverages the strengths of both models to achieve better generalization on unseen data.

---

## Models Used
- **RoBERTa** – fine-tuned for text-based emotion recognition.  
- **DistilBERT** – a lightweight transformer optimized for faster inference.  
- **Meta-Model (Ensemble Layer)** – combines outputs from both base models to produce final predictions.

---

## Dataset
A **licensed/private dataset** containing text samples annotated with emotion labels was used.  
The dataset includes multiple emotion categories, providing a diverse and realistic benchmark for model evaluation.

---

## Technologies & Libraries
- **PyTorch**
- **Hugging Face Transformers**
- **scikit-learn**
- **pandas**
- **numpy**
- **matplotlib**
- **joblib**

---

## How to Run

### Install Dependencies
```bash
pip install -r requirements.txt
