# GPT-2 from Scratch

Implementing a GPT-2 style Transformer language model from scratch to understand how large language models work internally.

---

## 📌 Project Overview

This project focuses on building a GPT-2–like autoregressive language model **from first principles**,first without using pretrained weights.
After that we implement pre-trained weights from OpenAI
The goal is educational: to deeply understand the Transformer architecture and text generation pipeline.

The entire implementation is contained in a Jupyter Notebook.

---

## 🎯 Objectives

- Understanding Byte-Pair Encoding
- Understand the Transformer architecture
- Implement self-attention and multi-head attention
- Build token and positional embeddings
- Train an autoregressive language model
- Generate text using the trained model

---

## 📁 Project Structure
GPT-2-from-scratch/
├── GPT2_from_scratch.ipynb
├── README.md

## 🛠 Tech Stack

- Python
- PyTorch
- NumPy
- Jupyter Notebook
- Tiktoken 

---

## 📚 Concepts Covered

- Tokenization
- Normalisation Layer
- Embedding layers
- Positional encoding
- Multi-head self-attention
- Transformer blocks
- Residual connections & LayerNorm
- Language model training
- Text generation

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/dhruvi003/GPT-2-from-scratch.git
   cd GPT-2-from-scratch

2. Install dependencies:
   ```bash
   pip install torch numpy notebook

3. Open the notebook:
    ```bash
   jupyter notebook

---

## 📈 Future Improvements

- Train on larger datasets
- Add batching and dataloaders
- Track training loss visually
- Scale to GPT-2 small architecture
- Compare outputs with pretrained GPT-2

--- 

## 📖 References

Building GPT-2 from Scratch playlist by Vizuara 
"Language Models are Unsupervised Multitask Learners" – OpenAI
Transformer Architecture (Attention Is All You Need)
