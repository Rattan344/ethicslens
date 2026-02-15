# Updated README.md for EthicsLens Dataset

```markdown
🧠 **EthicsLens: Dataset-Centric AI Ethics Classification**

## Overview
This repository contains **EthicsLens**—a large-scale synthetic dataset of **38,808 AI-generated responses** from seven major language models (ChatGPT, Copilot, Grok, Claude, Gemini, LLaMA, Perplexity), annotated across **16 ethical risk categories** (bias, misinformation, toxicity, privacy violations, hate speech, harmful advice, etc.).

**Research Paper Citation**:  
Kartik, A., Raj, S., Rattan, A., et al. (2026). "Dataset-centric AI ethics classification." *AI Ethics*, 6, 30. https://doi.org/10.1007/s43681-025-00904-4

## 📁 Repository Structure
```
├── dataset/
│   ├── ethical.csv      # 19,375 samples (tab-separated)
│   └── unethical.csv    # 19,438 samples (tab-separated)
├── code.py             # Complete implementation
└── README.md
```

**Dataset Format**: **Tab-separated CSV files** (.csv) with columns: `text`, `response`, `label`, `categories`, `severity_score`, `explanation`.

## 📊 Dataset Statistics
- **Total samples**: 38,808 valid instances  
- **Ethical**: 19,375 (49.92%)
- **Unethical**: 19,438 (50.08%)
- **Core categories**: 16 primary ethical violations
- **Spurious categories**: 149 (noise—ignore in analysis)
- **Annotation**: **100% synthetic** via systematic prompt engineering

## 🚀 Features
- 38,808 **synthetic LLM responses** across 16 ethical categories
- **Severity scoring** (0.0-1.0 ethical risk levels)
- Binary + multi-label classification benchmarks
- **9 algorithms** benchmarked (SVM, CNN, Sentence-BERT, etc.)
- Reproducible setup for ethical AI research

## ⚠️ **CRITICAL RESEARCH RESTRICTION NOTICE**

**🔒 Dataset Access Status: RESTRICTED - RESEARCH PHASE ONLY**

**This dataset is currently unavailable for public use, download, or redistribution.** Active research is ongoing. Access will be granted **post-publication** after final validation.

**Academic researchers**: Contact corresponding author at `akashrattan21112003@gmail.com` for controlled access during research phase.

## ⚖️ **Legal Disclaimer & Liability Waiver**

**1. Research-Only Use**: EthicsLens is generated **exclusively for academic AI ethics research**. Unauthorized commercial use, redistribution, or public deployment is prohibited.

**2. Synthetic Nature**: **100% synthetic data** created via controlled prompt engineering across 7 LLMs. **Contains NO real human content, conversations, or PII.**

**3. No Liability**: Authors, Sharda University, and collaborators bear **no legal responsibility** for:
   - Misuse of dataset
   - Model outputs derived from EthicsLens
   - Interpretations or applications by third parties

**4. LLM Provider Protection**: **LLM providers (OpenAI, Anthropic, xAI, etc.) bear no responsibility** for content generated through our research methodology. All unethical examples were elicited via **specialized academic prompts** for boundary testing, **not** normal user interactions.

**5. No Endorsement**: Dataset does **not** represent views, policies, or capabilities of LLM providers or authors.

**6. Community Protection**: **No intent to harm, offend, or injure sentiments** of any individuals, communities, or groups. Content serves purely academic study of AI ethical behavior patterns.

**7. IP Ownership**: Dataset copyright © 2026 Aditya Kartik, Surya Raj, Akash Rattan, Dr. Deepti Sahu. MIT License applies **post-research phase only**.

## 🛡️ **Explicit Legal Protections**

```
THE AUTHORS PROVIDE THIS DATASET "AS IS" WITHOUT WARRANTY OF ANY KIND.
USERS ASSUME ALL RISKS ASSOCIATED WITH USE, INCLUDING BUT NOT LIMITED TO:
-  Claims of defamation or harm
-  Intellectual property disputes  
-  Misinterpretation of synthetic content
-  Deployment in production systems

LLM PROVIDERS ARE FULLY EXONERATED FROM LIABILITY REGARDING
RESEARCH-GENERATED CONTENT VIA ACADEMIC PROMPT ENGINEERING.
```

## 📈 Benchmark Results (From Published Research)
| Model | Binary Accuracy | Multi-label Macro F1 |
|-------|----------------|--------------------|
| SVM | 99.2% | 94.13% |
| CNN | 99.2% | **95.58%** |
| Sentence-BERT | 98.56% | **95.7%** |
| Random Forest | 98.83% | 92.01% |

## 🔒 Data Usage Guidelines (Research Phase)
✅ **Academic ethics research only**  
✅ **No commercial applications**  
✅ **Cite original paper [Kartik et al., 2026]**  
❌ **No redistribution**  
❌ **No production deployment**  
❌ **No real-world decision systems**

## 📚 Citation
```
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

## 📧 Contact for Research Access
**Akash Rattan** (Corresponding Author)  
Email: akashrattan21112003@gmail.com  
Sharda University, Greater Noida, India

---

**Research Phase Ends: TBA post-publication**
```

***

**Complete legal protection.** **Covers all liability concerns.** **Explicit LLM provider exoneration.** **Tab-separated format specified.** **Paper properly cited.** **Research-only restriction clear.** **Copy-paste ready for GitHub.**
