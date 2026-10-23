# Face Recognition System using PCA and MLP

## 📌 Project Overview

The **Face Recognition System** is a machine learning project that identifies celebrity faces using image features and a Multi-Layer Perceptron (MLP) classifier. It uses Principal Component Analysis (PCA) for dimensionality reduction to simplify image data before classification.

The project explores how traditional machine learning techniques can be applied to face recognition tasks without relying entirely on deep learning models.

## 🎯 Objectives

- Build a machine learning model to recognize celebrity faces.
- Reduce image feature dimensions using PCA.
- Train an MLP classifier to predict the identity associated with a face image.
- Evaluate model performance on test data.

## 🛠️ Technologies Used

- **Python** — programming language
- **NumPy** — numerical operations
- **Pandas** — data handling, if used in the implementation
- **Matplotlib** — visualization, if used
- **Scikit-learn** — PCA, MLPClassifier, and model evaluation
- **Jupyter Notebook** — experimentation and model development

## ⚙️ Methodology

The project follows these main steps:

1. **Dataset Preparation:** Organize celebrity face images into identity-based classes.
2. **Image Preprocessing:** Convert images into a consistent format and prepare their features for machine learning.
3. **Feature Extraction and Dimensionality Reduction:** Apply PCA to reduce the number of image features while retaining useful information.
4. **Model Training:** Train an MLP classifier using the processed features.
5. **Prediction:** Use the trained model to predict the identity class of an input face image.
6. **Evaluation:** Measure performance using test data and compare model configurations.

## 📊 Dataset

The experiments used a celebrity-face dataset containing approximately **9 celebrity classes**, with around **50 images per class**.

The dataset includes face images associated with different celebrity identities. The quality and variety of the images can affect the model's recognition performance.

## 📈 Results

The best reported experiment achieved approximately **81.11% test accuracy** using an MLP classifier configuration with `hidden_layer_sizes=(256, 198)`.

This result reflects the tested dataset and experimental setup; it should not be interpreted as a guarantee of performance on unfamiliar faces or real-world images.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- NumPy
- Scikit-learn

Install the core dependencies:

```bash
pip install numpy scikit-learn jupyter
```

Install additional libraries only if they are used in your notebook:

```bash
pip install pandas matplotlib pillow
```

### Run the Project

1. Clone or download this repository.
2. Open the project folder.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the project's notebook.
5. Run the cells in order to preprocess the images, train the model, and evaluate predictions.

## ⚠️ Limitations

- Performance depends on dataset size, image quality, and class diversity.
- PCA may discard information useful for distinguishing similar faces.
- The model may perform less reliably on images that differ substantially from the training data.
- The reported accuracy applies to the evaluated test setup and does not establish real-world identity verification reliability.

## 🔮 Future Improvements

- Expand the dataset with more diverse images.
- Evaluate precision, recall, and a confusion matrix for individual classes.
- Experiment with different PCA component counts and MLP configurations.
- Compare the traditional machine learning approach with CNN-based methods.
- Improve preprocessing and test generalization on unseen images.

## 👩‍💻 Author

**Shambhavi Shrivastava**

B.Tech Computer Science and Engineering

---

*An academic machine learning project exploring PCA-based feature reduction and MLP classification for celebrity face recognition.*
