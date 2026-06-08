# Fish Species Classification Using Machine Learning

## Overview

This project implements a Computer Vision and Machine Learning pipeline for fish species classification using handcrafted image features.

The system extracts:

* Shape Features
* Color Features
* Texture Features (GLCM)

and compares the performance of several Machine Learning algorithms:

* Support Vector Machine (SVM)
* Random Forest
* K-Nearest Neighbor (KNN)
* Gaussian Naive Bayes

The dataset used is the A Large Scale Fish Dataset.

---

## Dataset

Dataset:

A Large Scale Fish Dataset
Source: https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

Classes used in this project:

* Sea Bass
* Red Mullet

---

## Feature Extraction

### Shape Features

* Aspect Ratio
* Solidity
* Circularity

### Color Features

* Mean Hue
* Mean Saturation
* Mean Value

### Texture Features (GLCM)

* Contrast
* Correlation
* Energy
* Homogeneity

---

## Project Workflow

1. Load fish images
2. Image preprocessing
3. Shape extraction
4. Color extraction
5. Texture extraction using GLCM
6. Create feature dataset
7. Filter selected fish species
8. Train Machine Learning models
9. Evaluate model performance
10. Compare results

---

## Models Evaluated

### Support Vector Machine (SVM)

Kernel:

* RBF

### Random Forest

Parameters:

* 100 Trees

### K-Nearest Neighbor (KNN)

Parameters:

* k = 5

### Gaussian Naive Bayes

Standard Gaussian distribution assumption.

---

## Libraries Used

* OpenCV
* NumPy
* Pandas
* Scikit-Learn
* Scikit-Image
* Matplotlib
* Seaborn
* OpenPyXL

---

## Results

The project compares the accuracy of:

| Model         | Accuracy |
| ------------- | -------- |
| SVM           | XX.XX%   |
| Random Forest | XX.XX%   |
| KNN           | XX.XX%   |
| Naive Bayes   | XX.XX%   |

Replace the values above with your experimental results.

---

## Visualizations

* Confusion Matrix
* Feature Importance
* Accuracy Comparison

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Fish-Classification-ML.git
cd Fish-Classification-ML
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate:

Windows

```bash
venv\Scripts\activate
```

Linux / MacOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
Fish.ipynb
```

---

## Author

Computer Vision Project

Machine Learning-Based Fish Species Classification
