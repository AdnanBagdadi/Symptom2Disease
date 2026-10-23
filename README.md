Symptom2Disease: BERT vs. TF-IDF

This project classifies free-text symptom descriptions into one of 24 diseases and compares two NLP approaches on the same stratified 70/15/15 split:

Frozen BERT + dense head: a pretrained BERT encoder used as a feature extractor, with a small classifier trained on its [CLS] embedding.
TF-IDF + Logistic Regression: a traditional baseline using unigram and bigram features.

The two models are effectively tied (a one-sample difference), but TF-IDF trains in seconds and is easier to interpret.

Includes: text cleaning, EDA, both models, per-class reports and confusion matrices, custom prediction, saved weights, and a Gradio app that runs both models side by side.

Run it: open the notebook in Google Colab, run all cells top to bottom, and upload Symptom2Disease.csv when prompted.

Academic project only. Not for medical diagnosis.
