🧠 EthicsLens: Dataset-Centric AI Ethics Classification
📌 Overview

EthicsLens is a large-scale synthetic dataset containing 38,808 AI-generated responses collected from seven major language models:

ChatGPT

Copilot

Grok

Claude

Gemini

LLaMA

Perplexity

Each response is annotated across 16 core ethical risk categories, including bias, misinformation, toxicity, privacy violations, hate speech, harmful advice, and related ethical dimensions.

📄 Research Paper
Kartik, A., Raj, S., Rattan, A., Sahu, D. (2026). Dataset-centric AI ethics classification.
AI Ethics, 6, 30.
https://doi.org/10.1007/s43681-025-00904-4

📂 Repository Structure
EthicsLens/
│
├── dataset/
│   ├── ethical.csv        # 19,375 samples (tab-separated)
│   └── unethical.csv      # 19,438 samples (tab-separated)
│
├── code.py                # Full experimental implementation
└── README.md

📄 Dataset Format

File type: .csv

Encoding: UTF-8

Separator: Tab-separated

Columns:

text
response
label
categories
severity_score
explanation

📊 Dataset Statistics

Total samples: 38,808 valid instances

Ethical: 19,375 (49.92%)

Unethical: 19,438 (50.08%)

Core categories: 16

Spurious categories: 149 (noise; excluded in analysis)

Annotation type: 100% synthetic (controlled prompt engineering)

🚀 Key Features

38,808 synthetic LLM responses

Binary + multi-label classification setup

16 primary ethical risk dimensions

Severity scoring (0.0 – 1.0)

9 benchmarked ML/DL algorithms (SVM, CNN, Sentence-BERT, Random Forest, etc.)

Fully reproducible academic pipeline

⚠️ Dataset Access Status
🔒 RESTRICTED – Research Phase Only

This dataset is currently unavailable for public download, redistribution, or commercial use.

Access will be granted post-publication after final validation.

📩 Academic researchers may request controlled access:

Akash Rattan
Email: akashrattan21112003@gmail.com

Sharda University, Greater Noida, India

⚖️ Legal Disclaimer & Liability Waiver
1️⃣ Research-Only Use

EthicsLens is generated exclusively for academic AI ethics research.
Unauthorized commercial use or redistribution is prohibited.

2️⃣ Synthetic Nature

This dataset is 100% synthetic.
It contains:

No real human conversations

No personal data

No personally identifiable information (PII)

3️⃣ No Liability

The authors, collaborators, and Sharda University bear no legal responsibility for:

Misuse of the dataset

Model outputs derived from EthicsLens

Interpretations or third-party applications

4️⃣ LLM Provider Protection

LLM providers (e.g., OpenAI, Anthropic, xAI, Google, Meta) bear no responsibility for content generated via this research methodology.
All unethical examples were elicited via specialized academic prompts for boundary testing.

5️⃣ No Endorsement

The dataset does not represent the views, policies, or capabilities of any LLM provider or author.

6️⃣ Community Protection

There is no intent to harm, offend, or injure sentiments of any individual or community.
All content serves purely academic study of AI ethical behavior.

7️⃣ Intellectual Property

Copyright © 2026
Aditya Kartik, Surya Raj, Akash Rattan, Dr. Deepti Sahu

MIT License applies after research phase completion only.

🛡 Explicit Legal Protection Statement
THE DATASET IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND.

USERS ASSUME ALL RISKS ASSOCIATED WITH USE, INCLUDING BUT NOT LIMITED TO:
- Claims of defamation
- Intellectual property disputes
- Misinterpretation of synthetic content
- Deployment in production systems

LLM PROVIDERS ARE FULLY EXONERATED FROM LIABILITY
REGARDING RESEARCH-GENERATED CONTENT.

📈 Benchmark Results (Published)
Model	Binary Accuracy	Multi-label Macro F1
SVM	99.2%	94.13%
CNN	99.2%	95.58%
Sentence-BERT	98.56%	95.70%
Random Forest	98.83%	92.01%
📚 Citation

If you use this work, please cite:

@article{kartik2026,
  title={Dataset-centric AI ethics classification},
  author={Kartik, Aditya and Raj, Surya and Rattan, Akash and Sahu, Deepti},
  journal={AI Ethics},
  volume={6},
  pages={30},
  year={2026},
  doi={10.1007/s43681-025-00904-4}
}

📜 Data Usage Guidelines (Research Phase)

✅ Academic ethics research only
✅ Citation of original paper required
❌ No redistribution
❌ No commercial deployment
❌ No production decision systems

📌 Research Phase

Research Phase Ends: Post-publication (TBA)
