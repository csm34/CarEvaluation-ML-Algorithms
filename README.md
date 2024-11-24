# Car Evaluation Analysis and Machine Learning Project

This repository contains a comprehensive analysis of the **UCI Car Evaluation Dataset**. The project includes exploratory data analysis (EDA), machine learning model training, and a **Streamlit app** for interactive exploration of the data and results. 

## Dataset Information

The dataset, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/19/car+evaluation), evaluates the acceptability of cars based on several attributes:

- **Features:**
  - `buying`: Buying price (vhigh, high, med, low)
  - `maint`: Maintenance cost (vhigh, high, med, low)
  - `doors`: Number of doors (2, 3, 4, 5more)
  - `persons`: Passenger capacity (2, 4, more)
  - `lug_boot`: Size of luggage boot (small, med, big)
  - `safety`: Safety rating (low, med, high)
- **Target:**
  - `class`: Car acceptability categories (unacc, acc, good, vgood)

The dataset has 1,728 entries, all of which are complete (no missing values), and it is designed for classification tasks.

## Features of the Project

### Exploratory Data Analysis (EDA)
The EDA section provides insights into the dataset's structure, feature distributions, and relationships:
- Value counts for categorical features.
- Visualizations such as bar plots and heatmaps to understand feature distributions and correlations.

### Machine Learning Models
The following algorithms were implemented to classify car acceptability:
1. **Support Vector Machine (SVM)**
2. **Random Forest**
3. **Logistic Regression**

Each model was evaluated using:
- Accuracy
- Classification Report
- Confusion Matrix (visualized as a heatmap)

### Streamlit Application
A user-friendly **Streamlit app** is included to explore the dataset and interact with the trained models. Users can:
- Select feature values to view car acceptability.
- Visualize predictions and model performance metrics.

## Getting Started

### Installation
1. Clone the repository:
   ```bash
   https://github.com/csm34/CarEvaluation-ML-Algorithms.git
   cd car-evaluation-project
   ```
2. Launch the app locally with:
    ```bash
   streamlit run app.py
   ```

