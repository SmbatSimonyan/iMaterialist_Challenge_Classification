# 🪑 iMaterialist Furniture Classification

A deep learning computer vision project that classifies furniture images into multiple categories using Convolutional Neural Networks (CNNs) built with TensorFlow and Keras.

This project was developed using the **Kaggle iMaterialist Challenge – Furniture 2018** dataset and demonstrates a complete image classification pipeline, including data preprocessing, model training, evaluation, and prediction.

---

## 📌 Project Overview

Image classification is one of the most important tasks in computer vision. In this project, a Convolutional Neural Network (CNN) is trained to recognize different categories of furniture from images.

The project follows an end-to-end machine learning workflow, from loading and preprocessing images to training, evaluating, and generating predictions.

This repository serves as both a learning resource and a portfolio project demonstrating practical deep learning skills.

---

## 🚀 Features

- Multi-class image classification
- Image preprocessing and normalization
- Data augmentation
- TensorFlow/Keras implementation
- CNN-based deep learning model
- Model training and validation
- Performance visualization
- Prediction on unseen furniture images
- Jupyter Notebook implementation

---

## 🧠 Model Architecture

The project uses a Convolutional Neural Network (CNN) consisting of:

- Convolutional Layers
- ReLU Activation
- MaxPooling Layers
- Batch Normalization
- Dropout Layers
- Fully Connected (Dense) Layers
- Softmax Output Layer

The network learns high-level visual representations of furniture images for accurate classification.

---

## 📂 Dataset

This project uses the **iMaterialist Challenge – Furniture 2018** dataset provided by Kaggle.

**Competition:**

https://www.kaggle.com/competitions/imaterialist-challenge-furniture-2018

The dataset contains thousands of furniture images belonging to numerous product categories.

Typical dataset structure:

```
dataset/
│
├── train/
├── validation/
└── test/
```

Each image is associated with a furniture category label.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Pillow
- Jupyter Notebook

---

## 📁 Project Structure

```
iMaterialist_Challenge_Classification/
│
├── furniture_classification_solution.ipynb
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── models/
├── images/
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/SmbatSimonyan/iMaterialist_Challenge_Classification.git
```

Navigate into the project

```bash
cd iMaterialist_Challenge_Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
furniture_classification_solution.ipynb
```

---

## ▶️ Usage

Run the notebook sequentially to:

1. Load the furniture dataset
2. Preprocess images
3. Train the CNN model
4. Evaluate model performance
5. Predict furniture categories on new images

---

## 📊 Model Evaluation

Model performance can be evaluated using:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Classification Report
- Confusion Matrix (if implemented)

---

## 📈 Future Improvements

- Transfer Learning (EfficientNetB0, EfficientNetV2, ResNet50, DenseNet121)
- Vision Transformers (ViT)
- Hyperparameter optimization
- Mixed Precision Training
- TensorFlow Lite deployment
- Flask/FastAPI REST API
- Streamlit web application
- ONNX model export

---

## 💻 Requirements

- Python 3.10+
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Pillow
- Jupyter Notebook

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork this repository and submit a Pull Request.

---

## 👨‍💻 Author

**Smbat Simonyan**

GitHub:

https://github.com/SmbatSimonyan

---

## 📚 Competition

**Kaggle**

iMaterialist Challenge – Furniture 2018

https://www.kaggle.com/competitions/imaterialist-challenge-furniture-2018

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.