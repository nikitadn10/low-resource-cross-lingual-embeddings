# Low-Resource Cross-Lingual Embedding Adaptation

## Project Overview

This project improves multilingual sentence embeddings for low-resource languages by fine-tuning a pretrained multilingual Sentence Transformer on Hindi-English parallel sentence pairs. The adapted model is evaluated using semantic retrieval metrics, translation probing, and embedding visualizations.

---

## Features

- Fine-tunes multilingual sentence embeddings
- Uses Hindi-English parallel corpus (OPUS-100)
- Contrastive learning with MultipleNegativesRankingLoss
- Evaluates Recall@1, Recall@5, Recall@10, MRR, and Median Rank
- Visualizes embeddings using UMAP
- Performs translation quality probing
- Includes error analysis of retrieval results

---

## Technologies Used

- Python
- PyTorch
- Sentence Transformers
- Hugging Face Datasets
- Transformers
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- UMAP

---

## Dataset

- **Dataset:** OPUS-100 Hindi-English Parallel Corpus
- **Source:** https://huggingface.co/datasets/Helsinki-NLP/opus-100