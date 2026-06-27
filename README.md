# GPT-2 Next Word Predictor

A deep learning project that fine-tunes OpenAI's GPT-2 model for **next-word prediction** and **text generation** using the WikiText-2 dataset. The project demonstrates how transformer-based language models can learn contextual language patterns and generate coherent text.

---

## 📌 Overview

This project fine-tunes a pre-trained GPT-2 language model on the WikiText-2 dataset using the Hugging Face Transformers library. After training, the model predicts the most probable next words for a given prompt and generates context-aware text continuations.

The project also evaluates the model using standard language modeling metrics such as **Perplexity** and **Top-5 Accuracy**.

---

## 🚀 Features

- Fine-tunes the GPT-2 language model
- Next-word prediction using probability distribution
- Context-aware text generation
- Evaluation using Perplexity and Top-5 Accuracy
- Custom inference functions for prediction and text generation
- Built with PyTorch and Hugging Face Transformers

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- GPT-2
- WikiText-2 Dataset

---

## 📂 Project Structure

```
├── notebooks/
│   └── GPT2_Next_Word_Predictor.ipynb
├── trained_model/
├── logs/
├── README.md
└── requirements.txt
```

---

## 📖 Dataset

**Dataset:** WikiText-2 (wikitext-2-raw-v1)

The dataset contains high-quality Wikipedia articles and is widely used for language modeling tasks.

---

## ⚙️ Model Architecture

- Pre-trained GPT-2 Language Model
- Tokenizer: GPT2Tokenizer
- Sequence Length: 128
- Framework: PyTorch
- Fine-tuning using Hugging Face Trainer API

---

## 🏋️ Training Configuration

| Parameter | Value |
|----------|-------|
| Model | GPT-2 |
| Epochs | 1 |
| Learning Rate | 5e-5 |
| Batch Size | 1 |
| Weight Decay | 0.01 |
| Optimizer | AdamW (Trainer Default) |

---

## 📊 Evaluation Metrics

The model was evaluated on the validation dataset using:

- **Perplexity:** 40.82
- **Top-5 Accuracy:** 59.57%

These metrics indicate the model's ability to predict the next token and generate coherent text.

---

## 💡 Example Predictions

### Prompt

```
Every innovation begins with
```

### Top Predictions

```
1. the
2. a
3. an
```

### Generated Output

```
Every innovation begins with the first use, and then it must be made...
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/gpt2-next-word-predictor.git
cd gpt2-next-word-predictor
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook or Google Colab notebook and execute all cells.

The notebook performs:

- Dataset loading
- Tokenization
- Fine-tuning GPT-2
- Evaluation
- Next-word prediction
- Text generation

---

## 📈 Future Improvements

- Train for multiple epochs
- Use larger datasets
- Fine-tune GPT-2 Medium or GPT-2 Large
- Hyperparameter optimization
- Beam Search and Top-k decoding
- Deploy as a web application using Streamlit or Gradio

---

## 📚 References

- Hugging Face Transformers
- Hugging Face Datasets
- OpenAI GPT-2
- WikiText-2 Dataset

---

## 👨‍💻 Author

**Siddharth Jeedula**

B.Tech Chemical Engineering  
IIT Bombay
