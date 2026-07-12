# Pretrained Models

This directory provides links to the pretrained transformer models developed for the research paper:

> **Lightweight and Explainable Neural Models for Multilingual Movie Script Certification**  
> Pratik N. Kalamkar, Prasadu Peddi, and Yogesh K. Sharma  
> *International Journal of Information Technology and Computer Science (IJITCS), 2026*  
> DOI: https://doi.org/10.5815/ijitcs.2026.02.09

---

## Overview

The published models are multilingual DistilBERT teacher models fine-tuned for automated movie script age-rating classification.

Supported languages:

- English
- Hindi
- Marathi

All models are based on:

> **distilbert-base-multilingual-cased**

---

# Available Models

| Language | Hugging Face Model |
|----------|--------------------|
| English | https://huggingface.co/pratikkalamkar/moviecert-teacher-en |
| Hindi | https://huggingface.co/pratikkalamkar/moviecert-teacher-hi |
| Marathi | https://huggingface.co/pratikkalamkar/moviecert-teacher-mr |

---

# Intended Use

These models are intended for:

- Automated movie script certification
- Movie content analysis
- Multilingual text classification
- Academic NLP research
- Benchmarking transformer models
- Explainable AI research

---

# Base Model

All published models are fine-tuned from:

```
distilbert-base-multilingual-cased
```

using the Hugging Face Transformers library.

---

# Related Resources

## Source Code

https://github.com/pratik1986/Lightweight-and-Explainable-Neural-Models-for-Multilingual-Movie-Script-Certification

---

## Datasets

### English

https://huggingface.co/datasets/pratikkalamkar/Movie_Scripts_with_Age_Ratings_by_Pratik_Kalamkar-EN

### Hindi

https://huggingface.co/datasets/pratikkalamkar/Movie_Scripts_with_Age_Ratings_by_Pratik_Kalamkar-Hi

### Marathi

https://huggingface.co/datasets/pratikkalamkar/Movie_Scripts_with_Age_Ratings_by_Pratik_Kalamkar-Mr

---

## Journal Paper

Paper PDF

https://www.mecs-press.org/ijitcs/ijitcs-v18-n2/IJITCS-V18-N2-9.pdf

DOI

https://doi.org/10.5815/ijitcs.2026.02.09

---

# Citation

If you use these pretrained models in your research, please cite:

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

# License

The pretrained models are distributed under the **Apache License 2.0**.

---

# Author

**Pratik N. Kalamkar**

GitHub:
https://github.com/pratik1986

Hugging Face:
https://huggingface.co/pratikkalamkar
