# Dialogue Summarization with FLAN-T5

This project fine-tunes a pre-trained **FLAN-T5** language model for the task of **dialogue summarization** using the Hugging Face Transformers framework.

The goal is to improve the ability of the model to generate concise summaries from multi-turn conversations.

---

## Project Overview

Large Language Models (LLMs) such as FLAN-T5 already possess strong zero-shot summarization capabilities.
In this project, we further improve the performance by **fine-tuning the model on a dialogue summarization dataset**.

The pipeline includes:

1. Loading a dialogue dataset
2. Tokenizing conversations and summaries
3. Fine-tuning a pre-trained FLAN-T5 model
4. Generating summaries for unseen dialogues
5. Evaluating model performance
