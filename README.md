# 🧠 Gemma Fine-Tuning & Inference Comparison

This repository contains notebooks and utilities for:
1. Cleaning and preparing conversational training data.  
2. Fine-tuning **Gemma-3** using supervised fine-tuning (SFT).  
3. Distilling knowledge from **MedGemma-4B** into **Gemma-3**.  
4. Comparing inference quality and latency across:
   - `medgemma-4b`
   - `gemma-3` (base)
   - `gemma-3-finetuned`
   - `gemma-3-finetuned-distilled`

---

## 📁 Repository Structure

| File | Description |
|------|--------------|
| `training_data_cleaning_notebook.ipynb` | Cleans and formats raw training data into Gemma chat-template JSONL. |
| `inference_generator.ipynb` | Runs inference and latency benchmarks for different models. |
| `README.md` | (This file) Documentation and workflow overview. |

---

## ⚙️ Setup

```bash
git clone <your-repo-url>
cd <repo>
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt


## Benchmarks


<img width="1752" height="433" alt="gemma3-benchmark" src="https://github.com/user-attachments/assets/655337f5-95fc-4a91-9e6f-643165932440" />
