# Lab 7: Large Language Models (LLMs)

## Overview
In this lab, I explored the three main Transformer model families: decoder-only, encoder-decoder, and encoder-only. The goal was to understand the differences between Transformer architectures and how pre-trained language models can perform various NLP tasks without training them from scratch.

## Models & Tasks Explored
* **Decoder-Only (DistilGPT-2):** Explored open-ended text generation.
* **Encoder-Decoder (FLAN-T5):** Handled instruction-based tasks, specifically translation and text summarization.
* **Encoder-Only (DistilBERT):** Performed sentiment classification on various sentences.

## Key Experiments
* **Task Routing:** Evaluated and compared how each model family is fundamentally structured to handle specific NLP tasks.
* **Sampling & Randomness (Optional Challenge):** Experimented with text generation using sampling. By removing the random seed, I observed how the same prompt produces different outputs due to the probability distribution used when choosing the next token.

## Technologies Used
* Python
* Hugging Face `transformers`
* PyTorch
