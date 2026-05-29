# Supervised Machine Learning

Project ini berisi implementasi dasar supervised machine learning menggunakan Python dan Scikit-learn untuk melakukan prediksi berdasarkan dataset numerik melalui proses preprocessing, training model, dan evaluasi model.

## Teknologi yang Digunakan

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Tujuan Project

Project ini bertujuan untuk:

* memahami konsep supervised learning,
* mempersiapkan dataset untuk machine learning,
* membangun model machine learning,
* melakukan training dan testing model,
* serta mengevaluasi performa model.

## Konsep yang Dipelajari

Beberapa konsep supervised learning yang dipelajari:

* feature dan target
* train-test split
* preprocessing data
* scaling data
* training model
* prediction
* model evaluation

## Workflow Machine Learning

Tahapan yang dilakukan:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Selection
5. Train Test Split
6. Data Scaling
7. Model Training
8. Prediction
9. Model Evaluation

## Library yang Digunakan

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Machine Learning Library

Project menggunakan library:

```python
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
```

dan beberapa model supervised learning dari:

```python
sklearn
```

## Data Splitting

Dataset dibagi menjadi:
* [Movies Metadata](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
* [Ratings Small](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
* data training
* data testing

menggunakan:

```python
train_test_split()
```

Tujuannya agar model dapat diuji menggunakan data yang belum pernah dipelajari sebelumnya.

## Data Scaling

Normalisasi data dilakukan menggunakan:

```python
MinMaxScaler
```

agar setiap feature memiliki skala yang seragam.

## Visualisasi Data

Visualisasi dilakukan menggunakan:

* histogram
* scatter plot
* distribusi data
* analisis feature numerik

## Struktur Project

```text
project/
│
├── supervised_machine_learning.ipynb
├── data/
├── README.md
└── requirements.txt
```

## Cara Menjalankan

1. Install dependency:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

3. Buka notebook:

```text
supervised_machine_learning.ipynb
```

## Insight Pembelajaran

Melalui project ini dipelajari:

* dasar supervised machine learning,
* preprocessing data,
* feature engineering,
* training model,
* evaluasi model,
* serta workflow machine learning menggunakan Python.

## Tujuan Pembelajaran

Project ini cocok untuk:

* pemula machine learning,
* latihan supervised learning,
* pembelajaran workflow machine learning menggunakan Scikit-learn.
