# 🧠 AutoGluon Assignment Part 1

**Course:** AutoGluon for Kaggle Competitions & Tabular ML  
**Due:** Sunday Nov 2 @ 11:59 PM  
**Points:** 100 | **Submission:** GitHub repo + Video demo link

---

## 📁 Repository Overview

This repository contains my Colab notebooks and artifacts for **AutoGluon Assignment Part 1**, including:

1. **Kaggle Competition Tasks**
   - **IEEE Fraud Detection** (classification)
   - **California Housing Prices** (regression with AutoMM)

2. **AutoGluon Demonstration Tasks**
   - Tabular Quick Start (classification + regression)
   - Feature Engineering
   - Multimodal Tabular

All notebooks run successfully in **Google Colab** (GPU runtime, Mac M1 host).  
Each notebook includes **full outputs**, **artifacts**, and **environment snapshots** for reproducibility.

---

## 🧩 Part A – Kaggle Competition Work

| Task | Description | Colab Link |
|:--|:--|:--|
| IEEE Fraud Detection | Binary classification with AutoGluon Tabular on Kaggle dataset. Includes sampling for Colab RAM safety and submission generation. | [Colab Link](https://colab.research.google.com/drive/11qq_f5TMDolC32DlJSbcYnpKN4j93qhb#scrollTo=92370af1) |
| California Housing Prices | Regression using AutoGluon AutoMM on Kaggle’s *california-housing-prices* dataset. | [Colab Link](https://colab.research.google.com/drive/1vTwogcO35HZpZnkgZpfGwL0hmYvUxIR0#scrollTo=kB6MDpkYsB8r) |

---

## 🧪 Part B – AutoGluon Colab Demonstrations

| Section | Topic | Colab Link |
|:--|:--|:--|
| i.1 | **Tabular Quick Start (Classification + Regression)** | [Colab Link](https://colab.research.google.com/drive/1pUBxpck4boiPRd5_cg6mo8bqL97VbhLh#scrollTo=f4d1edc3d2f610f6) |
| i.2 | **Multimodal Tabular** | [Colab Link](https://colab.research.google.com/drive/1pI-KtW_xwarf5Vy0oNsMHog5R4ZBopPi?usp=sharing) |
| i.3 | **Automatic Feature Engineering** | [Colab Link](https://colab.research.google.com/drive/1P3kAwMJe_bAm6l-DOG13s9Mv6jUvm1Mx?usp=sharing) |

---

## 🎥 Video Walkthrough (Insert Links Below)

> Each clip (~1–2 min) walks through the notebook, output, and results.

| Notebook | Video Link |
|:--|:--|
| IEEE Fraud Detection | _[(https://youtu.be/dGSvpzTpMEg)]_ |
| California Housing Prices | _[https://youtu.be/aWUTHhYEmR0]_ |
| Tabular Quick Start | _[(https://youtu.be/l1GJeEGTe74)]_ |
| Multimodal Tabular | _[https://youtu.be/7NW-97kBCrE]_ |
| Feature Engineering | _[Paste video link]_ |

---

## 🧰 Environment Notes

- Runtime: **Google Colab (GPU T4 / A100)**  
- Python: 3.12  
- AutoGluon Version: ≥ 1.4.0  
- Installed with:  
  ```bash
  !pip install -U autogluon kaggle pandas numpy scikit-learn
