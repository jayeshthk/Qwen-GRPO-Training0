# Qwen-GRPO-Training

This repository contains the code and resources for training the Qwen model using the **GRPO** dataset, along with the
1.NuminaMath-TIR (For R1 Zero Training)
2.Bespoke-Stratos-17k (For R1 Training) datasets.
It is designed for high-performance causal language modeling ta The model follows the **DeepSeek R1 Zero Training Practice** for fine-tuning.

## Overview

This repository includes:

- The training code for fine-tuning the Qwen model on the GRPO dataset.
- A Python notebook showcasing the entire training pipeline.
- Pre-trained weights of the fine-tuned model hosted on Hugging Face for easy access.

## Key Features

- **DeepSeek R1 Zero Training Practice**: The training follows the best practices laid out in the DeepSeek R1 methodology, ensuring high-quality results.
- **Datasets Used**: GRPO, NuminaMath, and Bespoke Stratos, enabling the model to specialize in technical and mathematical domains.
- **Model Type**: Causal Language Model (CausalLM).

## Python Notebook

The repository contains a Jupyter notebook named `QWEN_GRPO_).ipynb` that details the entire training process:

- Data preprocessing and loading
- Model architecture setup and fine-tuning
- Hyperparameter optimization
- Evaluation and testing on specific tasks

You can open the notebook to see the step-by-step code for training the model using the **DeepSeek R1 Zero** methodology.

## How to Run => use colab or local jupyter/

3. Follow the instructions in the notebook to run the training pipeline.

### Training Flow

1. **Data Preprocessing**: Loads and processes the GRPO, NuminaMath, and Bespoke Stratos datasets.
2. **Model Setup**: Initializes the Qwen model for causal language modeling.
3. **Training**: Uses the DeepSeek R1 Zero Training practice for effective fine-tuning.
4. **Evaluation**: Evaluates the model on test sets specific to mathematical and technical domains.

## Model Weights

The fine-tuned Qwen model is available on Hugging Face for easy usage:

- **Hugging Face Repo**: [Qwen-GRPO-Training](https://huggingface.co/joe-xhedi/Qwen-GRPO-training)

## Notes

- The notebook is designed to be run interactively for easy modification and experimentation.
- Ensure you have sufficient GPU resources, as training can be resource-intensive.
- This repository follows a structured training approach with clear documentation.

## Thanks =>

1. Google Colab
2. [Deepseek-R1 paper](https://arxiv.org/pdf/2501.12948)
3. Huggingface, TRL,TF..
