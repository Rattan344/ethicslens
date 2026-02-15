# 🧠 EthicsLens: Dataset-Centric AI Ethics Classification

<div align="center">

![Status](https://img.shields.io/badge/Status-Research%20Phase-orange)
![License](https://img.shields.io/badge/License-Restricted-red)
![Dataset Size](https://img.shields.io/badge/Samples-38%2C808-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)

**A large-scale synthetic dataset for AI ethics classification across 7 major language models**

[📄 Paper](https://doi.org/10.1007/s43681-025-00904-4) • [📩 Request Access](#-dataset-access-status) • [📚 Citation](#-citation)

</div>

---

## 📌 Overview

**EthicsLens** is a comprehensive synthetic dataset containing **38,808 AI-generated responses** collected from seven major language models, each annotated across 16 core ethical risk categories.

### 🤖 Models Included

| Model | Provider |
|-------|----------|
| ChatGPT | OpenAI |
| Copilot | Microsoft |
| Grok | xAI |
| Claude | Anthropic |
| Gemini | Google |
| LLaMA | Meta |
| Perplexity | Perplexity AI |

### 🎯 Ethical Risk Categories

The dataset covers **16 core ethical dimensions**, including:

- 🚫 Bias & Discrimination
- ⚠️ Misinformation
- ☠️ Toxicity
- 🔒 Privacy Violations
- 💬 Hate Speech
- ⚕️ Harmful Advice
- And 10 additional ethical dimensions

---

## 📄 Research Paper

**Kartik, A., Raj, S., Rattan, A., Sahu, D. (2026).** *Dataset-centric AI ethics classification.*  
**AI Ethics**, Volume 6, Page 30.

🔗 **DOI:** [10.1007/s43681-025-00904-4](https://doi.org/10.1007/s43681-025-00904-4)

---

## 📂 Repository Structure

```
EthicsLens/
│
├── dataset/
│   ├── ethical.csv        # 19,375 samples (tab-separated)
│   └── unethical.csv      # 19,438 samples (tab-separated)
│
├── code.py                # Full experimental implementation
└── README.md              # This file
```

---

## 📊 Dataset Specifications

### 📄 File Format

| Property | Value |
|----------|-------|
| **File Type** | `.csv` |
| **Encoding** | UTF-8 |
| **Separator** | Tab-separated |

### 📋 Column Schema

| Column | Description |
|--------|-------------|
| `text` | Input prompt/query |
| `response` | LLM-generated response |
| `label` | Binary classification (ethical/unethical) |
| `categories` | Multi-label ethical categories |
| `severity_score` | Risk severity (0.0 - 1.0) |
| `explanation` | Rationale for classification |

### 📈 Dataset Statistics

<div align="center">

| Metric | Value |
|--------|-------|
| **Total Samples** | 38,808 |
| **Ethical Samples** | 19,375 (49.92%) |
| **Unethical Samples** | 19,438 (50.08%) |
| **Core Categories** | 16 |
| **Spurious Categories** | 149 (excluded) |
| **Annotation Type** | 100% Synthetic |

</div>

---

## 🚀 Key Features

✨ **38,808** synthetic LLM responses across 7 major models  
✨ **Binary + multi-label** classification setup  
✨ **16 primary** ethical risk dimensions  
✨ **Severity scoring** system (0.0 – 1.0 scale)  
✨ **9 benchmarked** ML/DL algorithms tested  
✨ **Fully reproducible** academic pipeline  
✨ **100% synthetic** – no real user data or PII

---

## ⚠️ Dataset Access Status

### 🔒 **RESTRICTED – Research Phase Only**

> **This dataset is currently unavailable for public download, redistribution, or commercial use.**

Access will be granted **post-publication** after final validation.

### 📩 Request Academic Access

**Academic researchers** may request controlled access by contacting:

**Akash Rattan**  
📧 Email: [akashrattan21112003@gmail.com](mailto:akashrattan21112003@gmail.com)  
🏛️ Affiliation: Sharda University, Greater Noida, India

---

## ⚖️ Legal Disclaimer & Liability Waiver

### 1️⃣ Research-Only Use

- EthicsLens is generated **exclusively for academic AI ethics research**
- Unauthorized commercial use or redistribution is **prohibited**

### 2️⃣ Synthetic Nature

This dataset is **100% synthetic** and contains:

- ❌ No real human conversations
- ❌ No personal data
- ❌ No personally identifiable information (PII)

### 3️⃣ No Liability

The authors, collaborators, and Sharda University bear **no legal responsibility** for:

- Misuse of the dataset
- Model outputs derived from EthicsLens
- Interpretations or third-party applications

### 4️⃣ LLM Provider Protection

**LLM providers** (e.g., OpenAI, Anthropic, xAI, Google, Meta) bear **no responsibility** for content generated via this research methodology.

- All unethical examples were elicited via specialized academic prompts for boundary testing
- Content does not reflect normal operation or safety measures of these systems

### 5️⃣ No Endorsement

The dataset **does not represent** the views, policies, or capabilities of any LLM provider or author.

### 6️⃣ Community Protection

- **No intent** to harm, offend, or injure sentiments of any individual or community
- All content serves **purely academic study** of AI ethical behavior

### 7️⃣ Intellectual Property

**Copyright © 2026**  
Aditya Kartik, Surya Raj, Akash Rattan, Dr. Deepti Sahu

**MIT License** applies after research phase completion only.

---

## 🛡️ Explicit Legal Protection Statement

> **THE DATASET IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND.**

**USERS ASSUME ALL RISKS ASSOCIATED WITH USE, INCLUDING BUT NOT LIMITED TO:**
- Claims of defamation
- Intellectual property disputes
- Misinterpretation of synthetic content
- Deployment in production systems

**LLM PROVIDERS ARE FULLY EXONERATED FROM LIABILITY REGARDING RESEARCH-GENERATED CONTENT.**

---

## 📈 Benchmark Results (Published)

Performance of various models on EthicsLens classification tasks:

| Model | Binary Accuracy | Multi-label Macro F1 |
|-------|----------------|---------------------|
| **SVM** | 99.2% | 94.13% |
| **CNN** | 99.2% | 95.58% |
| **Sentence-BERT** | 98.56% | 95.70% |
| **Random Forest** | 98.83% | 92.01% |

### 🏆 Key Findings

- Deep learning models achieve **near-perfect** binary classification
- Multi-label classification maintains **>92% macro F1** across all models
- Sentence-BERT shows best balance for multi-label tasks

---

## 📚 Citation

If you use this work in your research, please cite:

```bibtex
@article{kartik2026,
  title={Dataset-centric AI ethics classification},
  author={Kartik, Aditya and Raj, Surya and Rattan, Akash and Sahu, Deepti},
  journal={AI Ethics},
  volume={6},
  pages={30},
  year={2026},
  doi={10.1007/s43681-025-00904-4}
}
```

---

## 📜 Data Usage Guidelines (Research Phase)

### ✅ Permitted Uses

- ✅ Academic ethics research
- ✅ Educational purposes with proper citation
- ✅ Non-commercial analysis
- ✅ Benchmark comparisons with citation

### ❌ Prohibited Uses

- ❌ Redistribution without permission
- ❌ Commercial deployment
- ❌ Production decision systems
- ❌ Any use without proper citation

---

## 📌 Research Phase Timeline

| Milestone | Status |
|-----------|--------|
| **Paper Publication** | ✅ Published (2026) |
| **Research Phase** | 🟡 Active |
| **Public Release** | 🔴 TBA (Post-publication validation) |

---

## 👥 Authors

- **Aditya Kartik** - Lead Researcher
- **Surya Raj** - Co-Researcher  
- **Akash Rattan** - Co-Researcher | Contact Person
- **Dr. Deepti Sahu** - Principal Investigator

**Institution:** Sharda University, Greater Noida, India

---

## 🤝 Contributing

This is a research dataset currently in restricted access phase. For:

- **Access requests** → Contact [Akash Rattan](mailto:akashrattan21112003@gmail.com)
- **Collaboration proposals** → Email with detailed research plan
- **Bug reports in code** → Open an issue (after access is granted)

---

## 📞 Contact

For inquiries, collaboration, or access requests:

**Akash Rattan**  
📧 akashrattan21112003@gmail.com  
🏛️ Sharda University, Greater Noida, India

---

## ⭐ Acknowledgments

We thank:
- All LLM providers for their publicly available models
- The AI Ethics research community
- Sharda University for institutional support

---

<div align="center">

**Made with ❤️ for responsible AI research**

[![Paper](https://img.shields.io/badge/DOI-10.1007%2Fs43681--025--00904--4-blue)](https://doi.org/10.1007/s43681-025-00904-4)

</div>
