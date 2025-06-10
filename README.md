# Arabic LLMs for Poetry Generation & Classification

This project explores fine-tuning and evaluating Arabic large language models (LLMs) — including **AraGPT-2**, **AraT5**, and **Jais** — for the tasks of poetry generation and classification. It also includes metric-based benchmarking and multitask learning using AraBERT.

## Project Overview

Low-resource languages like Arabic often lack specialized NLP tools for creative domains like poetry. This project aims to:
- Generate coherent, metrical Arabic poetry using fine-tuned generative models.
- Benchmark outputs using metrics such as **Self-BLEU**, **perplexity**, and **rhyme fidelity**.
- Classify Arabic poems by type using a multitask neural architecture.

## Notebooks

- `AraBERT_Multitask.ipynb`: Multitask classification model for Arabic poetry.
- `AraT5.ipynb`: Fine-tuning AraT5 for Arabic poetry generation.
- `AraT5_selfbleu2.ipynb`: Evaluation using Self-BLEU and other metrics.
- `Jais_Code.ipynb`: Preliminary code for using the Jais model for Arabic text generation.

##  Evaluation Metrics

- **Self-BLEU** to evaluate diversity.
- **Perplexity** for model confidence.
- **Rhyme/Metre Fidelity** using custom evaluation scripts.

## Tech Stack

- Hugging Face Transformers
- PyTorch + PEFT (Parameter-Efficient Fine-Tuning)
- scikit-learn
- NLTK for BLEU scoring
- Datasets from the Arabic poetry corpus (not included due to size)

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/arabic-llm-poetry.git
   cd arabic-llm-poetry
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open any notebook in Jupyter and run it:
   ```bash
   jupyter notebook
   ```

*Created by [Maria Boxwala](mailto:maria@boxwala.com) – bridging creativity and computation in Arabic NLP.*
