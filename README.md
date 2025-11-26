# Mini-GPT From Scratch

Implementation of a small GPT-style language model from scratch, following “Let’s build GPT: from scratch, in code” by Andrej Karpathy.

## 🚀 What this repo does

- Implements tokenization, transformer blocks, attention mechanism and training loop in pure Python (with minimal dependencies)  
- Trains on a small text dataset to generate next-token predictions  
- Demonstrates core principles behind modern LLMs  

## 📦 Project Structure

```
mini-gpt-from-scratch/
├── gpt.ipynb         # Jupyter notebook with full implementation
├── gpt.py            # (optional) plain-python script version
├── data/             # (optional) dataset used for training
├── README.md
├── .gitignore
└── outputs/          # (optional) sample outputs, logs
```

## ▶️ How to Run

1. Clone this repo  
2. (Optional) create virtual environment and install requirements, e.g. `pip install torch numpy`  
3. Open `gpt.ipynb` in Jupyter Notebook and run all cells  

## 📚 What you’ll learn

- Transformer architecture basics: attention, multi-head attention, positional encoding  
- Tokenization & data preprocessing  
- Training and generation of text via next-token prediction  

## 🧠 Why this matters

Understanding how GPT works at a low level is critical for deeper study — including model evaluation, interpretability, security, and future custom LLM building.  

## 📝 License

[MIT License](LICENSE) — feel free to use, modify and learn from this code.
