
# CMSC472 Final Project: FULL_CAPACITY_MODEL_BERT

This repository contains the final project for CMSC472, which investigates BERT-based models for fake news classification. The project explores various preprocessing techniques, model fine-tuning strategies, and performance evaluations using a dataset of news entries.

## 📂 Files

- `CMSC472_Final_Report.pdf`: The final written report detailing the methodology, experiments, results, and conclusions.
- `FULL_CAPACITY_MODEL_BERT_Copy_of_Final.ipynb`: The Jupyter Notebook used to conduct data preprocessing, model training, and evaluation of results.

## 🧠 Project Introduction

Fake news is everywhere, especially in recent years as access to technology spreads and the world
becomes further politicized. We wish to use a deep learning algorithm to create a model that evaluates
a news article to determine its authenticity. Our decided approach is to use a Long Short-Term
Memory (LSTM) network as it is well suited for sequential data, which we have with text articles. In
terms of representing the written data numerically, we used a pre-trained BERT model to generate
embeddings, which values word importance and context in a text. The combination of these methods,
with data and text preprocessing, gave us a trainable model that can pick out key characteristics of
a fake news article and use them as predictors for determining authenticity of test articles at 96%
accuracy.

### Objectives

- Fine-tune BERT for fake news classification.
- Explore the impact of different preprocessing pipelines.
- Evaluate performance using accuracy and confusion matrices.

## 📊 Results

- Achieved improved accuracy through full-capacity fine-tuning of the BERT model.
- Confusion matrix analysis revealed challenges with less frequent classes.

## 🔧 Setup

To run the notebook:

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/cmsc472-bert-emotion-classifier.git
   cd cmsc472-bert-emotion-classifier
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv env
   source env/bin/activate  # or .\env\Scripts\activate on Windows
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Then open `FULL_CAPACITY_MODEL_BERT_Copy_of_Final.ipynb`.

## 📚 Dependencies

- Python 3.7+
- PyTorch
- Transformers (Hugging Face)
- scikit-learn
- pandas
- matplotlib
- seaborn
- tqdm
