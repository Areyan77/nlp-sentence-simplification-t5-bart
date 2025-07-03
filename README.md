# Simplifying Sentences with Small Transformers: A Comparative Study of T5 and BART

A Natural Language Processing (NLP) research project evaluating the performance of **T5-small** and **BART-base** for English sentence-level text simplification.

## 📘 Overview

This project fine-tuned two compact transformer models (T5-small, BART-base) using the WikiLarge dataset on Google Colab. The goal: enhance accessibility by simplifying complex sentences.

## 🚀 Models & Tools

- 🤖 T5-small (Text-to-Text)
- 🤖 BART-base (Denoising Autoencoder)
- 📚 Dataset: WikiLarge
- 🛠 Tools: Hugging Face Transformers, PyTorch, Colab (T4 GPU)

## 📊 Evaluation Metrics

| Metric    | T5-small | BART-base |
|-----------|----------|-----------|
| BLEU      | 0.2652   | 0.3087    |
| ROUGE-1   | 0.5952   | 0.6208    |
| SARI      | 36.13    | 38.25     |
| FKGL      | 10.02    | 10.09     |

## 📄 Contents

- 📝 `docs/NLP_Project_Report.pdf` — full research report
- 📓 `notebooks/NLP_Project.ipynb` — training and evaluation
- 🧪 Evaluation scripts using BLEU, ROUGE, SARI, FKGL
- 📦 Fine-tuned models (optional, hosted or linked)

## 💡 Findings

- **BART-base** outperformed T5-small across most metrics.
- **T5-small** required less GPU and trained faster—suitable for low-resource devices.
- Both models produced outputs around 10th-grade reading level — still complex for intended audience.

## 📌 Authors

- Ugyen Tshering
- Abdullahi Adewole Zakariyah
- Nima Yoezer
- Areyan Muhemed Ali Hussein

