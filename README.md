# LORA_maths_tiny_llama_gsm8k
This repository contains a **QLoRA fine-tuned adapter** built on top of:  Base Model: TinyLlama-1.1B-Chat-v1.0   Dataset: GSM8K (Grade School Math 8K)  The model is fine-tuned to improve **step-by-step mathematical reasoning** using chain-of-thought prompting.


Comparision
Evaluating Base TinyLlama...

100%|██████████| 165/165 [12:35<00:00, 4.58s/it] Base TinyLlama Accuracy: 1.29%

Evaluating Fine-Tuned (Merged)...

100%|██████████| 165/165 [12:40<00:00, 4.61s/it] Fine-Tuned (Merged) Accuracy: 1.90%

Training was performed using:

Transformers
PEFT
TRL SFTTrainer
BitsAndBytes
