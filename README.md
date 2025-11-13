Here’s the updated **README.md** version with your request included — it clearly states that the dataset is **not publicly usable until ongoing research is completed**:

---

# 🧠 EthicsLens: Dataset-Centric AI Ethics Classification

### Overview

This repository contains the full implementation and dataset structure used in the research project **“Dataset-Centric AI Ethics Classification.”**

The project introduces **EthicsLens**, a large-scale dataset of **38,808 AI-generated responses** from seven major language models, annotated across **16 ethical risk categories** (e.g., bias, misinformation, toxicity, privacy violations, hate speech, harmful advice, etc.).

It provides a **benchmarking framework** for detecting ethical and unethical AI-generated content using both **traditional machine learning** and **deep learning** models.

---

## 📁 Repository Structure

```
├── dataset/
│   ├── ethical.csv
│   ├── unethical.csv
│   
│
├── code.py # all implementation code in one file
│   
│
└── README.md
```

* **`dataset/`** → Contains the EthicsLens dataset (currently restricted access).
* **`code/`** → Contains all model training, preprocessing, and evaluation scripts.

---

## 🚀 Features

* 38,808 annotated AI-generated responses
* 16 defined ethical violation categories with severity scoring
* Binary and multilabel classification frameworks
* Benchmarks across 9 algorithms (SVM, CNN, Sentence-BERT, etc.)
* Synthetic annotations with consistency checks and explainability fields
* Reproducible setup for ethical AI benchmarking

---

## ⚙️ How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/EthicsLens.git
   cd EthicsLens
   ```

2. **Set up environment:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the main code file:**

   ```bash
   python code/ethicslens_classification.py
   ```

---

## 📊 Dataset Information

* **Total samples:** 38,808
* **Ethical samples:** 19,375
* **Unethical samples:** 19,438
* **Core categories:** 16
* **Spurious categories (noise):** 149 — to be ignored in analysis
* **Annotation method:** Synthetic prompt engineering via seven LLMs
* **Severity scores:** Range 0.0–1.0 indicating ethical risk level

⚠️ **Important Notice:**
The dataset included in this repository is currently **restricted**.
It is **not open for public use, download, or redistribution** until the completion of the ongoing research phase.
Access will be granted after the final validation and publication of related studies.

---

## 📈 Benchmark Summary

| Model         | Binary Accuracy | Multilabel Macro F1 |
| ------------- | --------------- | ------------------- |
| SVM           | **99.2%**       | 94.13%              |
| CNN           | **99.2%**       | 95.58%              |
| Sentence-BERT | 98.56%          | **95.7%**           |
| Random Forest | 98.83%          | 92.01%              |

---

## 📘 Citation

If you use or reference this work, please cite:

```
Rattan, A. (2025). Dataset-Centric AI Ethics Classification. GitHub Repository.
https://github.com/Rattan344/ethicslens
```

---

## 🔒 Data Usage and Ethics

The **EthicsLens dataset** has been generated solely for academic and ethical AI research.
It does **not** include personal, identifiable, or real human conversation data.

Researchers must adhere to the following:

* Do **not** use or distribute the dataset until official permission is granted.
* Limit experiments to AI-generated content contexts.
* Acknowledge all dataset and methodology references when reused.

---
