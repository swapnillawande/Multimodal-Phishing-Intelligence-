# 🛡️ Multimodal Phishing Intelligence

### Explainable Multimodal Phishing Detection Using Email, URL, and Webpage Fusion

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)]()
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Phishing%20Detection-green.svg)]()
[![Research](https://img.shields.io/badge/Research-Cybersecurity-red.svg)]()

---

## 📖 Overview

Phishing remains one of the most prevalent cybersecurity threats, exploiting human trust through deceptive emails, malicious URLs, and fraudulent websites.

Traditional phishing detection systems typically rely on a single source of evidence, such as email content, URL structure, or webpage characteristics. While effective in specific scenarios, these approaches often struggle against modern phishing campaigns involving:

* URL obfuscation
* Brand impersonation
* Credential harvesting
* Visual cloning
* Social engineering
* Multi-stage phishing attacks

This project proposes a **Multimodal Phishing Intelligence Framework** that integrates:

* 📧 Email Content Analysis
* 🔗 URL and Domain Analysis
* 🌐 Webpage Content Analysis

to improve phishing detection accuracy, robustness, and operational reliability.

---

## 🎯 Research Objectives

The primary objectives of this project are:

* Improve phishing detection performance through multimodal evidence fusion.
* Evaluate the contribution of individual modalities.
* Analyze phishing behavior across different attack scenarios.
* Improve detection robustness against phishing obfuscation techniques.
* Support explainable cybersecurity decision-making.
* Reduce analyst workload through improved alert prioritization.

---

## 🏗️ Framework Architecture

```text
Email Content
      │
      ▼
Email Classifier

URL Features
      │
      ▼
URL Classifier

Webpage Features
      │
      ▼
Webpage Classifier

      ▼
Multimodal Fusion Layer

      ▼
Risk Scoring

      ▼
Final Classification

(Phishing / Legitimate)
```

---

## 📊 Datasets

The framework utilizes publicly available phishing datasets covering multiple modalities.

| Modality | Dataset                           |
| -------- | --------------------------------- |
| Email    | Kaggle Phishing Email Dataset     |
| URL      | PhiUSIIL Phishing URL Dataset     |
| Webpage  | Mendeley Phishing Website Dataset |

Dataset references are available in:

```text
datasets/dataset_links.txt
```

---

## ⚙️ Technologies Used

### Programming

* Python
* Jupyter Notebook

### Data Processing

* Pandas
* NumPy
* BeautifulSoup

### Machine Learning

* Scikit-learn
* Logistic Regression
* TF-IDF Vectorization

### Visualization

* Matplotlib
* Seaborn

---

## 📂 Repository Structure

```text
Multimodal-Phishing-Intelligence/

├── README.md

├── notebooks/
│   └── Multimodal_Phishing_Intelligence.ipynb

├── figures/
│   ├── Figure1.pdf
│   ├── Figure2.pdf
│   └── ...

├── tables/
│   ├── Results.csv
│   ├── Results.csv
│   └── ...

├── datasets/
│   └── dataset_links.txt

├── docs/
│   ├── methodology.md
│   ├── architecture.md
│   └── results_summary.md

└── .gitignore
```

---

## 🔬 Experimental Setup

The study evaluates:

### Unimodal Models

* Email-only
* URL-only
* Webpage-only

### Bimodal Models

* Email + URL
* Email + Webpage
* URL + Webpage

### Trimodal Model

* Email + URL + Webpage

---

## 📈 Results

### Best Performing Configuration

**Email + URL + Webpage Fusion**

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 96.3% |
| Precision | 95.8% |
| Recall    | 95.1% |
| F1-Score  | 95.4% |
| ROC-AUC   | 0.987 |

### Key Findings

✅ Multimodal fusion consistently outperformed unimodal baselines.

✅ Combining email, URL, and webpage evidence improved phishing detection robustness.

✅ Different phishing attack scenarios rely on different evidence sources.

✅ Fusion reduced false positives and improved classification reliability.

✅ The framework demonstrated strong performance across multiple phishing attack categories.

---

## 🚀 Running the Project

### Clone Repository

```bash
git clone https://github.com/swapnillawande/Multimodal-Phishing-Intelligence-.git

cd Multimodal-Phishing-Intelligence-
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib beautifulsoup4 jupyter
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Multimodal_Phishing_Intelligence.ipynb
```

---

## 📄 Publication

**Title**

Multimodal Phishing Intelligence Using Email, URL, and Webpage Fusion for Attack Detection

---

## 👨‍💻 Author

**Swapnil Sunil Lawande**

Master of Software Engineering

University of Europe for Applied Sciences

Berlin / Potsdam, Germany

---


