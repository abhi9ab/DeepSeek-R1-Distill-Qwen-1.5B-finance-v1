# DeepSeek-R1-Distill-Qwen-1.5B-Finance-v1 (Fine-tuned with LoRA)

**This repository contains the fine-tuned version of the DeepSeek-R1-Distill-Qwen-1.5B model for financial tasks, named DeepSeek-R1-Distill-Qwen-1.5B-Finance-v1. The fine-tuning was performed using LoRA (Low-Rank Adaptation) on a subset of the Josephgflowers/Finance-Instruct-500k dataset.**

---

## Model Details

- Base Model: DeepSeek-R1-Distill-Qwen-1.5B
- Fine-Tuning Method: LoRA
- Fine-Tuned Model: DeepSeek-R1-Distill-Qwen-1.5B-Finance-v1
- Dataset: Josephgflowers/Finance-Instruct-500k (reduced to 5k JSONL entries)
- Platform: Free-tier Google Colab
- Library: Hugging Face Transformers

---

## Objective

The goal of this model is to enhance the base model's performance on financial tasks by fine-tuning it on a specialized financial dataset. Using LoRA, this model has been optimized for low-rank adaptation, allowing efficient fine-tuning with fewer resources.

---

## Dataset

The model was fine-tuned on a subset of the Finance-Instruct-500k dataset from Hugging Face, specifically reduced to 5,000 JSONL entries for the fine-tuning process. This dataset contains financial questions and answers, providing a rich set of examples for training the model.

---

## Setup and Usage

**Requirements:**
- Python >= 3.10
- Hugging Face Transformers library
- Google Colab (for free-tier usage)
- PyTorch

---

## Installation

1. Clone this repository:
```bash
git clone https://github.com/your-username/DeepSeek-R1-Distill-Qwen-1.5B-Finance-v1.git
cd DeepSeek-R1-Distill-Qwen-1.5B-Finance-v1
```
2. Follow the instructions mentioned in the notebook

---

## Notes

- This fine-tuning was performed on the free-tier of Google Colab, so training time and available resources are limited.
- Ensure that your runtime in Colab is set to a GPU environment to speed up the training process.
- The reduced 5k dataset is a smaller sample for experimentation. You can scale this up depending on your needs and available resources.

---

## License

[MIT](https://github.com/abhi9ab/DeepSeek-R1-Distill-Qwen-1.5B-finance-v1/blob/main/LICENSE)

---
