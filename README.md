# GPT-OSS-20b Red-Teaming Challenge

A schema-driven, PII-safe red-teaming pipeline for the **OpenAI GPT-OSS-20b Hackathon**.  
This project detects risky outputs, redacts sensitive data, and validates submissions against the official Harmony Findings JSON schema.

---

## 🚀 Features
- **PII Redaction** – Removes emails, phone numbers, and API keys from prompts/responses.
- **Schema Compliance** – Validates JSON output against the competition’s `findings.schema`.
- **Reproducible Pipeline** – Deterministic execution for consistent results.
- **Multi-Turn Prompt Probing** – Detects context-drift jailbreaks in interactive storytelling.
- **CC0 Licensed** – Fully open for reuse, as required by competition rules.

---

## 📂 Repository Structure
```
.
├── Red-Teaming_Challenge.ipynb   # Main notebook pipeline
├── findings.schema               # Official Harmony Findings schema
├── example-harmony-findings.json # Example submission format
├── my-finding-1.json              # Generated test submission
├── README.md
└── LICENSE
```

---

## ⚙️ Installation
```bash
git clone https://github.com/<your-username>/gpt-oss-20b-red-teaming.git
cd gpt-oss-20b-red-teaming
pip install -r requirements.txt
```

---

## 🛠️ Usage
1. **Prepare schema & example files**  
   Ensure `findings.schema` and `example-harmony-findings.json` are in the working directory.

2. **Run the notebook**  
   Open `Red-Teaming_Challenge.ipynb` in Jupyter Lab/Notebook or VS Code and execute cells sequentially.

3. **Validate submission**  
   The pipeline outputs a JSON file that passes schema validation and is ready for Kaggle submission.

---

## 📜 License
This repository is licensed under the **Creative Commons CC0 1.0 Universal** license.  
You are free to copy, modify, distribute, and perform the work, even for commercial purposes, all without asking permission.  
[View full license text](https://creativecommons.org/publicdomain/zero/1.0/)

---

## 🏆 Competition Reference
- **Title:** Red-Teaming Challenge – OpenAI GPT-OSS-20b  
- **Host:** OpenAI & Kaggle  
- **URL:** [Competition Page](https://www.kaggle.com/competitions/openai-gpt-oss-20b-red-teaming)
