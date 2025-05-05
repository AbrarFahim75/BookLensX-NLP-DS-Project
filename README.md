# BookLensX-NLP-DS-Project

A multi-task NLP system for book title rating prediction, genre classification, and intelligent title generation using BERT, T5, and other large language models.

---

## Project Overview

**BookLensX** integrates three natural language processing tasks into a single multi-task learning pipeline:
- **Rating Prediction** (regression)
- **Genre Classification** (multi-class classification)
- **Title Generation** (sequence-to-sequence generation)

The system uses shared encoders (e.g., BERT, RoBERTa) with task-specific output layers. T5 or BART models are used for the generation task. The training process uses a joint multi-task loss function.

---

## Technologies Used

- Python 3.x
- PyTorch
- Hugging Face Transformers
- Sentence-BERT
- Scikit-learn
- Jupyter Notebook
- Google Colab or Kaggle for GPU training

---

## Project Structure (Planned)
