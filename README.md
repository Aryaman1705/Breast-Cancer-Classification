# Breast-Cancer-Classification
This repository provides a machine learning solution for breast cancer classification using the Wisconsin Breast Cancer Dataset. The goal is to classify breast tumors as **malignant** or **benign** based on the input features extracted from cell nuclei in a biopsy.

---

## Overview

Breast cancer is a common and potentially life-threatening condition that can benefit significantly from early diagnosis. This project leverages machine learning algorithms to classify breast cancer tumors with high accuracy using labeled datasets. It demonstrates the complete pipeline for preprocessing, training, testing, and evaluating machine learning models.

---

## Features

- **Dataset:** Uses the Wisconsin Breast Cancer Dataset available from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).
- **Algorithms Implemented:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - Artificial Neural Netwroks
- **Data Preprocessing:**
  - Handles missing values and scales the data for machine learning models.
- **Visualization:**
  - Heatmaps and plots to analyze feature correlations and evaluate model performance.

---

## Installation

### Prerequisites

Make sure you have Python 3.7+ installed along with the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

### Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/idhanwal/Breast-Cancer-Classification.git
cd Breast-Cancer-Classification
```

---

## Results
   - Model evaluation metrics such as confusion matrix, accuracy, k-fold score are displayed in the console.
   - Visualization of correlations and model predictions are saved or displayed.

---

## Project Structure

```
Breast-Cancer-Classification/
├── breast-cancer.csv     # dataset
├── .ipynb file           # Google Colab
├── README.md             # Documentation
```

---

## License

This project is licensed under the GNU Genral Public License V3. See the [LICENSE](https://github.com/Aryaman1705/Breast-Cancer-Classification?tab=GPL-3.0-1-ov-file#) file for details.

---

## Acknowledgments

- Wisconsin Breast Cancer Dataset provided by UCI Machine Learning Repository.
- Scikit-learn library for model training and evaluation.

---
