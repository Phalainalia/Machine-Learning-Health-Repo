# Machine Learning & Health Predictions

> This series of Colab projects explores the possibilities that lie in the intersection between medical science and Machine Learning. The project is centered around exploring several ML tecniques, most of them in order to detect, classify, identify diseases throughout diverse areas of health.

---

## Overview

This project uses basics of ML and a series of medical dataset to explore statistics, distributions and populations of diseases in order to classify them or detect them through sheer raw data.

The Data is stored in the Data Folder of the directory. This folder contains diverse .csv files that unfold the statistics of Diabetes, Hypertension, Heart Disease, Obesity and even Brain Cancer detecion.

The data contained ranges from population statistics such as height, age, regular habits, gender, blood type etc. in a csv format, to encephalograms and image data.

All data sources can be found as specified by each of the Colabs, usually through Kaggle or GitHub.

---

## Results

Each of the Colab shows the predictions, results and analysis made to identify and unfold the special characteristics and hidden informatino that the relationships of each files data could yield.

Results and analysis are displayed in a variety of graphs, classifications and evaluation metrics ussualy used in the area.

---

## Methodology

### Data preprocessing:

Usually, the data preprocessing just consist of cleansing the initial dataset in order to work freely. Homogeneizing data types, cleansing NaN, ordering the dataframes etc.

### Models:

The models featured in the notebook are the core of the ML area:

- K-Means
- Decision Trees
- DB-Scan
- SVM
- Kernels
- Neural Networks
- Convolutional Neural Networks

---

## Projects Structure

```bash
Machine Learning & Health Predictions/
├── CNN_NN_Encephalogram_Detection.ipynb
├── DB_Scan_Obesity.ipynb
├── Decision_Tree_&KMeans_Obesity.ipynb
├── k_means.ipynb
├── Keras_Neurone_Diabetes.ipynb
├── SVM_and_Kernel.ipynb
├── Data/
│   ├── data_wavelet.csv
│   ├── Diabetes.csv
│   ├── Hypertension.csv
│   ├── heart_disease.csv
│   ├── Obesity.csv
│   └── Cancer.zip

```

---

## Main Libraries

All libraries can be pip installed through the requirements.txt. (Just reminder, the version I included are functional as of 21/03/2026)

But the main libraries used are:

- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Plotly
- Matplotlib

---

Author: Diego A. Parra
