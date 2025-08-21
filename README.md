# Text Summarizer & Question Answering

An interactive web interface for **text summarization** and **question answering** using Hugging Face Transformers and Gradio.

---

## Features

- Summarize long text using `facebook/bart-large-cnn`.
- Answer questions from text using `distilbert-base-cased-distilled-squad`.
- Option to summarize the text first before answering.
- Simple and fast web UI with **Gradio**.

---

## Run Locally

### Installation

```bash
pip install gradio transformers torch
