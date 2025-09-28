# LLM-Detector-Experiments-HC3-Dataset
Experiments on detecting AI-generated vs human text (HC3 dataset, Mamba, RetNet, Electra, RoBERTa, etc.) using Colab + HuggingFace.

# 🧪 LLM-Detector-Experiments

Experiments on **detecting AI-generated vs human text** using the **HC3 dataset**.  
This repository benchmarks several recent transformer models including **Mamba, RetNet, Electra, and RoBERTa**, with HuggingFace + Google Colab integration.

---

## 📌 Overview
The rise of LLMs (e.g., ChatGPT, Claude, Gemini) has made **AI text detection** a pressing challenge.  
This project:
- Loads and preprocesses the **HC3 dataset** (Human vs ChatGPT answers).  
- Fine-tunes multiple models for **binary classification (Human=0, AI=1)**.  
- Evaluates results across metrics: **AUROC, Accuracy, F1-Micro, F1-Macro, Confusion Matrix**.  

The goal is to benchmark model families beyond standard transformers (e.g., **Mamba, RetNet**) and provide open results for reproducibility.

---

## 📊 Models Supported

- **Mamba** → State-space model checkpoint via HuggingFace Hub  
- **RetNet** → Efficient transformer alternative  
- **Electra** → Pretrained checkpoint (`google/electra-base-discriminator`)  
- **RoBERTa** → Pretrained checkpoint (`roberta-base`)  

---

## 📈 Metrics Logged

- AUROC  
- Accuracy  
- F1 (Micro & Macro)  
- Confusion Matrix  

