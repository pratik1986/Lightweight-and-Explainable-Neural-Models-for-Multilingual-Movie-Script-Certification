# Lightweight and Explainable Neural Models for Multilingual Movie Script Certification

Official implementation accompanying the journal paper:

**Lightweight and Explainable Neural Models for Multilingual Movie Script Certification**

---

## 📄 Journal Paper

**Published in:**

International Journal of Information Technology and Computer Science (IJITCS)

**Paper PDF**

https://www.mecs-press.org/ijitcs/ijitcs-v18-n2/IJITCS-V18-N2-9.pdf

**DOI**

https://doi.org/10.5815/ijitcs.2026.02.09

---

# Overview

This repository contains the official implementation accompanying the journal paper:

> **Lightweight and Explainable Neural Models for Multilingual Movie Script Certification**

The proposed framework automatically predicts movie age ratings from multilingual movie scripts using lightweight transformer models.

Supported languages:

-  English
-  Hindi
-  Marathi

Main contributions include:

- Multilingual transformer-based movie script classification
- Lightweight DistilBERT teacher models
- Knowledge distillation
- Temperature calibration
- Explainable AI
- Rule-based refinement
- Model quantization
- Complete reproducible implementation

---

# Repository Structure

```text
datasets/
models/
notebooks/
paper/
CITATION.bib
CITATION.cff
LICENSE
README.md

```

---

# Research Workflow

```text
Movie Scripts
      │
      ▼
Dataset Preparation
      │
      ▼
Teacher Model Training
      │
      ▼
Knowledge Distillation
      │
      ▼
Calibration
      │
      ▼
Explainability
      │
      ▼
Rule-based Refinement
      │
      ▼
Quantization
      │
      ▼
Evaluation
```

---

# 🤗 Pretrained Models

| Language | Hugging Face |
|----------|--------------|
| English Teacher | https://huggingface.co/pratikkalamkar/moviecert-teacher-en |
| Hindi Teacher | https://huggingface.co/pratikkalamkar/moviecert-teacher-hi |
| Marathi Teacher | https://huggingface.co/pratikkalamkar/moviecert-teacher-mr |

---

# 📦 Datasets

## English

- Hugging Face
  https://huggingface.co/datasets/pratikkalamkar/Movie_Scripts_with_Age_Ratings_by_Pratik_Kalamkar-EN

- Zenodo
  https://zenodo.org/records/20763133

- Kaggle
  https://www.kaggle.com/datasets/pratik2kcn/movie-scripts-with-age-ratings-pratik-kalamkar-en

---

## Hindi

- Hugging Face
  https://huggingface.co/datasets/pratikkalamkar/Movie_Scripts_with_Age_Ratings_by_Pratik_Kalamkar-Hi

- Zenodo
  https://zenodo.org/records/20764389

- Kaggle
  https://www.kaggle.com/datasets/pratik2kcn/movie-scripts-with-age-ratings-pratik-kalamkar-hi

---

## Marathi

- Hugging Face
  https://huggingface.co/datasets/pratikkalamkar/Movie_Scripts_with_Age_Ratings_by_Pratik_Kalamkar-Mr

- Zenodo
  https://zenodo.org/records/20764834

- Kaggle
  https://www.kaggle.com/datasets/pratik2kcn/movie-scripts-with-age-ratings-pratik-kalamkar-mr

---

# Combined Dataset Repository

https://github.com/pratik1986/Movie_Script_with_Age_Rating_by_Pratik_Kalamkar-EN-Hi-Mr

---

# Citation

If you use this repository, datasets or pretrained models in your research, please cite:

```bibtex
@article{kalamkar2026moviecertification,
  author = {Pratik N. Kalamkar and Prasadu Peddi and Yogesh K. Sharma},
  title = {Lightweight and Explainable Neural Models for Multilingual Movie Script Certification},
  journal = {International Journal of Information Technology and Computer Science},
  volume = {18},
  number = {2},
  pages = {146--160},
  year = {2026},
  doi = {10.5815/ijitcs.2026.02.09}
}
```

---

# Related Resources

📄 Journal Paper

https://www.mecs-press.org/ijitcs/ijitcs-v18-n2/IJITCS-V18-N2-9.pdf

💻 GitHub Repository

https://github.com/pratik1986/Lightweight-and-Explainable-Neural-Models-for-Multilingual-Movie-Script-Certification

🤗 Hugging Face Models

https://huggingface.co/pratikkalamkar

📦 Hugging Face Datasets

https://huggingface.co/pratikkalamkar?tab=datasets

---

# License

Apache License 2.0 for models
cc by-nc-sa 4.0 for datasets
