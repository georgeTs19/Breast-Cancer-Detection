# Breast Cancer Detection

## Overview
This project is focused on breast cancer classification using machine learning techniques. The dataset used is the built-in `breast_cancer` dataset from `sklearn`, which contains digitized images of breast cancer biopsies with various features extracted from the images. The primary objective is to evaluate different classification models and determine their effectiveness in distinguishing between malignant and benign cases.

## Features and Dataset
The dataset contains 30 numeric attributes representing cell nucleus characteristics, including:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

Each instance in the dataset is classified as either:
- Malignant (cancerous)
- Benign (non-cancerous)

## Methods Used
The project applies multiple machine learning algorithms, including:
- **Support Vector Machines (SVM)** (linear, polynomial, and RBF kernels)
- **Random Forest Classifier**
- **Gradient Boosting Classifier**


Additionally, **SMOTE (Synthetic Minority Over-sampling Technique)** is used to address class imbalance.

## Installation
To set up and run this project, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-detection.git
   cd breast-cancer-detection
    ```

2. Create a virtual environment (optional but recommended):
```bash
  python -m venv venv
  source venv/bin/activate  # On Windows use: venv\Scripts\activate
 ```

3. Install dependencies:
   ```bash
    pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook
   ```bash
     jupyter notebook
    ```

Open **Breast_Cancer_detection.ipynb** to explore the analysis and model training steps.



  
