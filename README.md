**SFT & DPO Fine-Tuning Project**

This repository explores two key approaches to fine-tuning large language models — Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO) — to align model behavior with human intent and task objectives.

**🚀 Project Overview**

## Supervised Fine-Tuning (SFT):
Trains the base model on curated instruction-response pairs to improve task performance and followability.

## Direct Preference Optimization (DPO):
Fine-tunes the model using human preference data to improve output quality, helpfulness, and alignment without explicit reward modeling.

**🧩 Key Features**

- Implementation of both SFT and DPO pipelines using the Hugging Face ecosystem

- Support for LoRA, PEFT, and quantized models for efficient fine-tuning

- Training scripts with Weights & Biases logging

- Example datasets for instruction and preference fine-tuning

- Comparison metrics and visualization of model improvements

**⚙️ Tech Stack**

- Frameworks: Transformers, TRL, PEFT

- Logging: Weights & Biases (wandb)

- Models: TinyLlama

**📊 Results**

Includes side-by-side performance comparison between:

SFT-only model outputs

DPO-aligned model outputs

**🌱 Next Steps**

Add RLHF or RLAIF for advanced alignment

Deploy with Gradio for quick model demos

Try domain-specific data (education, health, finance)
