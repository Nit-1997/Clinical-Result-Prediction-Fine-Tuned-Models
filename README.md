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

## Benchmarks

<img width="1302" height="499" alt="Screenshot 2025-11-03 at 12 14 35 AM" src="https://github.com/user-attachments/assets/ed7a6c35-5611-4bd3-bf68-5ca8d54cc3f2" />

<img width="1302" height="991" alt="Screenshot 2025-11-03 at 12 14 58 AM" src="https://github.com/user-attachments/assets/e27c7b78-c709-4f84-a60b-7a3d362e8163" />

<img width="1302" height="986" alt="Screenshot 2025-11-03 at 12 15 25 AM" src="https://github.com/user-attachments/assets/4df876f9-23ba-46b2-9287-9c9439aa281b" />

<img width="1302" height="513" alt="Screenshot 2025-11-03 at 12 15 46 AM" src="https://github.com/user-attachments/assets/2c34cb5c-cddd-4e34-b30a-7f065ced9b86" />




## ⚙️ Setup

```bash
git clone <your-repo-url>
cd <repo>
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
