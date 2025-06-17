# 🧾 AI Lease Contract Analyzer

This is a Streamlit web app that uses the Mistral 7B LLM via Ollama to extract key legal terms from PDF lease agreements. Built for analyzing residential leases, the app supports multi-file upload and generates concise, structured output.

## ⚙️ Features

- Upload one or more lease agreements in PDF format
- Automatically extracts:
  - Monthly Lease Rate
  - Lease Term
  - Security Deposit
  - Utilities Responsibility
  - Penalties/Fees
  - Property Use
- Clean markdown output
- Option to download all results as a `.txt` file

## 🚀 Demo

https://github.com/chatepri/ai-contract-analyzer/blob/main/media/demo.mp4

## 📁 Sample Files

Found in `/sample_leases/`:
- Rental_Lease Agreement1.pdf
- Rental_Lease Agreement2.pdf
- Rental_Lease Agreement3.pdf

## 🛠️ Getting Started

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the app:
```bash
streamlit run app/contractanalyzer.py
```

## 📦 Requirements

- `streamlit`
- `requests`
- `PyMuPDF`

## 📜 Legal

This tool provides automated extraction only and is not a substitute for professional legal advice.

---
