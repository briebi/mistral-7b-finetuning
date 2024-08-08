# Mistral 7B Fine-Tuning

This project involves fine-tuning the Mistral 7B model using QLoRA, guided by Brev.dev's tutorial ("Fine-tune Mistral - Own Data"). The aim is to adapt the model to domain-specific data for enhanced performance in natural language processing tasks.

## Project Overview

The Mistral 7B model has been fine-tuned to improve its handling of specialized data, focusing on optimizing performance for various NLP tasks. This project leverages Hugging Face Transformers, QLoRA, and tokenization techniques.

## Features

- **Fine-Tuning**: Applied QLoRA for efficient model adaptation.
- **Performance**: Enhanced model accuracy and performance with specific data.
- **Libraries**: Utilized Hugging Face Transformers and other machine learning tools.

## Files

**m-finetune_results.ipynb**: Contains the Jupyter Notebook I used to train the LLM, with all the corresponding outputs.
**m-finetune_empty.ipynb**: Empty Jupyter Notebook you can use to run on your own device
**notes.jsonl**: Series of question-answer pairs I generated from my AI philosophy course notes; used to train Mistral 7B
**notes-validation.jsonl**: Series of question-answer pairs used for validation in training Mistral 7B

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/briebi/mistral-7b-finetuning.git
2. Use the m-finetune_empty.ipynb to run it on your own device
3. Create a Brev.dev account and deploy a launchable using the NVIDIA A10G (24GiB) chip and create a container using Python and CUDA
4. Once the instance is running, drag the m-fintune_empty.ipynb, notes.jsonl, and notes-validation.jsonl files into Jupyter Notebook and run all the code
