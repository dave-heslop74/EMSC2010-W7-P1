# EMSC2010 – Week 7 Practical 1: Bayesian Inference with Real Data

This repository contains the template Jupyter notebook for **Week 7 Practical 1** of *EMSC2010: Data Science for Earth System Scientists* at the Australian National University.

The session applies the Bayesian inference techniques developed in Week 7 Lectorial 1 to a real dataset collected by the class.

---

## Notebook

### Notebook 1 – Indoor vs. Outdoor Air Pressure (`NB1`)

**Dataset:** Atmospheric pressure measurements collected by the class using the [Phyphox](https://phyphox.org/) smartphone app (*Pressure* sensor). Each student measures one indoor and one outdoor air pressure reading, and these are pooled to form the class dataset.

This is an open-ended challenge notebook. Using the `PyMC` workflow developed in **Notebook 3 of Week 7 Lectorial 1** (`EMSC2010-W7-L1-NB3`) as a template, students estimate the posterior distributions for the mean atmospheric pressure inside and outside the building, and use these posteriors to test whether the two means are meaningfully different.

**Key concepts:** Independent application of Bayesian inference, posterior estimation of population means, comparison of two groups using real, student-collected data

**Libraries:** `numpy`, `matplotlib`, `scipy`, `pymc`, `arviz`

---

## Getting Started

This is a **template repository**. To begin working on the notebook:

1. Click **"Use this template"** at the top of this page to create a copy of the repository in your own GitHub account.
2. Open the notebook from your copy of the repository and click the **"Open in Colab"** badge at the top of the notebook to launch it in Google Colab.
3. Before submitting, replace the `uXXXXXXX` placeholder in the filename with your ANU student UID.

---

## Repository Structure

```
EMSC2010-W7-P1/
├── EMSC2010_W7_P1_NB1_uXXXXXXX.ipynb   # Indoor vs. outdoor air pressure (Bayesian inference)
├── LICENSE
└── README.md
```

---

## Course Information

| | |
|---|---|
| **Course** | EMSC2010 – Data Science for Earth System Scientists |
| **Institution** | Australian National University (ANU) |
| **Week** | 7 |
| **Session** | Practical 1 |
| **Topic** | Bayesian Inference with Real Data |

---

## License

This repository is released under the [MIT License](LICENSE).
