<div align="center">

# 🩸 Diabetes Prediction with Deep Learning

**A Keras neural network that predicts diabetes from patient measurements.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`a.ipynb` trains a feed-forward neural network on the diabetes dataset in `2.1 diabetes.csv`:

1. Load and inspect the data with pandas.
2. Split and scale the features with scikit-learn.
3. Train a Keras binary classifier for **200 epochs** with a validation split.
4. Plot accuracy / loss curves - validation accuracy settles around **78-79 %**.

> ⚠️ Educational project - not for medical use.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/diabetes-deep.git
cd diabetes-deep
pip install tensorflow keras pandas numpy scikit-learn matplotlib jupyter
jupyter notebook a.ipynb
```

## 📁 Project Structure

```
.
├── a.ipynb            # Model training and evaluation
└── 2.1 diabetes.csv   # Dataset
```

## 🛠️ Tech Stack

`Keras` · `scikit-learn` · `pandas` · `NumPy` · `Matplotlib`
