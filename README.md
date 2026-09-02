 FusionGuard: CNN + LSTM + BERT Ensemble for Fake News Detection

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hakson-spec/Research_Paper_Code/blob/main/Research.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Official source code and interactive implementation for the research paper:  
"FusionGuard: CNN + LSTM + BERT Ensemble for Fake News Detection"

---

 📌 Overview

FusionGuard is a multi-branch ensemble architecture combining Convolutional Neural Networks (CNN), Long Short-Term Memory networks (LSTM), and Bidirectional Encoder Representations from Transformers (BERT) to classify and detect fake news articles.

---

 Interactive Execution via Google Colab

The easiest way to reproduce the results is directly in Google Colab (no local environment setup required):

1. Click the [Open in Colab](https://colab.research.google.com/github/Hakson-spec/Research_Paper_Code/blob/main/Research.ipynb) badge above.
2. In Colab, navigate to Runtime > Change runtime type and select T4 GPU.
3. Follow the dataset setup steps below before executing the cells.

---

Dataset Setup

This project uses the **Fake and Real News Dataset** available on Kaggle.

1. Download `Fake.csv` and `True.csv` from [Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).
2. In your Google Colab session:
   - Open the left sidebar by clicking the Files (folder icon).
   - Click Upload to session storage**.
   - Upload both `Fake.csv` and `True.csv` to the root `/content/` directory.

---

 Hardware & Runtime Requirements

- Runtime:Google Colab (Python 3.10+)
- Hardware Accelerator:T4 GPU (~15 GB VRAM recommended)
- Primary Dependencies:
  - `torch`
  - `transformers`
  - `tensorflow` / `tf-keras`
  - `scikit-learn`
  - `pandas`, `numpy`, `matplotlib`, `seaborn`

---

Repository Structure

```text
├── Research.ipynb       # Main interactive Jupyter notebook (Training, Evaluation, Visualizations)
└── README.md            # Documentation and instructions

 



