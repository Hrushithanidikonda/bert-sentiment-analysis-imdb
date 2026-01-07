# bert-sentiment-analysis-imdb
Fine-tuning a BERT-based Large Language Model for sentiment analysis on IMDb reviews.

# Fine-Tuning BERT for Sentiment Analysis (IMDb)

## 📌 Project Overview
This project demonstrates the fine-tuning of a Large Language Model (BERT) for binary sentiment
analysis using the IMDb movie reviews dataset. The performance of the fine-tuned model is compared
against a traditional TF-IDF + Logistic Regression baseline.

## 🧠 Problem Statement
Given a movie review, classify the sentiment as either:
- Positive
- Negative

## 📊 Dataset
- IMDb Movie Reviews (50,000 samples)
- Balanced dataset with equal positive and negative labels
- Source: Hugging Face Datasets

## 🏗️ Model Architecture
- Pre-trained BERT-based transformer
- Classification head added on top of the [CLS] token
- Fine-tuned end-to-end using supervised learning

## ⚙️ Training Details
- Optimizer: AdamW
- Learning Rate: 2e-5
- Epochs: 3
- Batch Size: 16
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score

## 📈 Results
| Model | Accuracy | F1-score |
|------|----------|----------|
| TF-IDF + Logistic Regression | ~0.88 | ~0.88 |
| Fine-tuned BERT | **0.92** | **0.92** |

## 🧪 Evaluation
- Confusion matrix analysis
- Training and validation loss monitoring
- Balanced performance across both sentiment classes

## 📁 Repository Structure

