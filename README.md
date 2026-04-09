# 📄 Arabic Document Understanding using Vision-Language Models (VLMs)
This project explores how Vision-Language Models (VLMs) can be leveraged to process and understand low-quality scanned Arabic documents, such as historical books and legal records.

Traditional OCR systems often struggle with:
- Complex layouts
- Noisy or low-resolution scans
- Arabic script variability

In this project, we go beyond standard OCR by utilizing the reasoning capabilities of VLMs to extract structured and meaningful information with higher accuracy.

---

## 🚀 What this project covers

### 🔹 Data Strategy
- Parsing complex PDF documents
- Handling Arabic text in challenging formats
- Generating synthetic data for domain-specific tasks

### 🔹 Model Development
- Fine-tuning Vision-Language Models using **LlamaFactory**
- Applying parameter-efficient techniques (LoRA)
- Handling multimodal inputs (image + text)

### 🔹 Infrastructure & Experimentation
- Training on scalable GPU infrastructure using **Vast.ai**
- Tracking experiments and metrics with **Weights & Biases (WandB)**

### 🔹 Deployment & Optimization
- Merging LoRA weights for efficient inference
- Optimizing model performance using **vLLM**

---

## 🎯 Goal

Build a robust pipeline capable of transforming noisy Arabic document images into structured, machine-readable data — enabling applications in digital archiving, legal tech, and historical data analysis.

---

## 🛠️ Tech Stack
Python | PyTorch | Vision-Language Models (VLMs) | LlamaFactory | LoRA | vLLM | WandB | Vast.ai

---

## 📌 Future Work
- Improve performance on extremely degraded scans  
- Expand dataset with diverse Arabic document types  
- Deploy as an API for real-world usage  


## Recommended Setup

### Download Miniconda from https://www.anaconda.com/download

### Steps to install WSL:

1. Open PowerShell as Administrator.
2. Run:
   ```powershell
   wsl --install

### Setup the environment
```bash
$ conda create --name myenv python=3.11
$ conda activate myenv
```

### Install the required packages
```bash
$ pip install -r requirements.txt
```

