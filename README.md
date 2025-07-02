# CTGAN-Synthetic-Data-Generator

This project demonstrates how to use **CTGAN (Conditional Tabular GAN)** to generate synthetic tabular data for classification tasks. The goal is to augment small datasets with high-quality synthetic samples to improve model performance.

---

## Overview

We use a real-world speech dataset to:

- Preprocess and encode categorical data
- Train a **CTGAN** model to synthesize realistic tabular records
- Evaluate a classifier (Random Forest) on augmented training sets
- Analyze how synthetic data impacts accuracy and F1-score

---

## Technologies & Libraries Used

- **CTGAN** – Synthetic data generation
- **Scikit-learn** – Classification and metrics
- **Pandas / NumPy** – Data wrangling
- **Matplotlib** – Performance visualization
- **Google Colab** – Runtime and testing

---

## Files Included

| File Name                          | Description                                  |
|------------------------------------|----------------------------------------------|
| `CTGAN-Internship.ipynb`           | Main notebook containing the entire workflow |
| `speech-final dataset(final).xlsx` | Required input dataset                       |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anchita2004/CTGAN-Synthetic-Data-Generator.git
   cd CTGAN-Synthetic-Data-Generator
