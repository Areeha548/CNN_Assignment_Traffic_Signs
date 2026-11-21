# 🚦 Traffic Sign Recognition using CNN

## 📌 Project Overview

This project is about **Traffic Sign Recognition using a Convolutional Neural Network (CNN)**.

The main goal is to train a deep learning model that can recognize and classify traffic signs into 43 different categories.

For example, when we provide an image of a traffic sign, the CNN model analyzes the image and predicts which traffic sign it represents.

This project uses the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

## 🎯 Project Objectives

- Explore and understand the traffic sign dataset.
- Preprocess images before training.
- Build a CNN model from scratch.
- Train the model to recognize 43 traffic sign classes.
- Improve model performance using different techniques.
- Evaluate model accuracy and analyze incorrect predictions.

## 📂 Dataset

This project uses the **GTSRB (German Traffic Sign Recognition Benchmark)** dataset.

The dataset contains images of different German traffic signs belonging to 43 classes.

The dataset is divided into:
- Training Data: Used to teach the model.
- Validation Data: Used to check model performance during training.
- Testing Data: Used to evaluate the final model.

## 🛠️ Technologies & Libraries

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Seaborn
- PIL (Pillow)

## 🧠 What Does This Notebook Cover?

### Part A: Data Exploration
- Load the GTSRB dataset.
- Display 25 random traffic sign images.
- Count images in each class.
- Identify the three least common classes.
- Check image dimensions.

### Part B: Data Preprocessing
- Resize images to 32 × 32 pixels.
- Convert images into tensors.
- Normalize pixel values between 0 and 1.
- Split training data into 80% training and 20% validation.
- Create DataLoaders for efficient training.

### Part C: Building a CNN Model
Build a CNN model from scratch using:
- Convolutional Layers
- ReLU Activation
- Max Pooling
- Flatten Layer
- Fully Connected Layers
- Dropout Layer

The model produces predictions for 43 traffic sign classes.

It also tracks training and validation loss and accuracy.

### Part D: Model Improvements

Three different techniques are tested to improve the baseline CNN model:

1. **Data Augmentation:** Creates slightly modified training images using rotation, shifting, zooming, and brightness changes.
2. **Dropout:** Helps reduce overfitting by randomly disabling some neurons during training.
3. **Class Weighting:** Gives more importance to less frequent classes during training.

The results are compared with the baseline model to identify which technique performs better.

### Part E: Model Evaluation

The selected model is evaluated using:
- Test Accuracy
- Confusion Matrix
- Classification Report
- Most Confused Class Pairs
- Per-Class Accuracy

Misclassified images are also displayed to understand where the model makes mistakes.

### Part F: Top-3 Predictions

The notebook also demonstrates predictions on a single traffic sign image.

It displays the three most likely classes along with their confidence scores.

## ⚙️ How to Run the Project

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Open the project folder**

```bash
cd YOUR_PROJECT_FOLDER
```

**3. Install the required libraries**

```bash
pip install torch torchvision numpy matplotlib pandas scikit-learn seaborn pillow jupyter
```

**4. Open Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open the notebook**

Open `CNN_Assignment_Traffic_Signs_Solved.ipynb` and run the cells from top to bottom.

The GTSRB dataset will be downloaded automatically during the first run. An internet connection is required for downloading it.

## 📊 Results

The notebook automatically generates:

- Training and validation accuracy graphs.
- Training and validation loss graphs.
- Model comparison table.
- Confusion matrix.
- Classification report.
- Top-3 prediction results.

The final test accuracy is calculated after running the notebook.

## 💡 What I Learned

Through this project, I learned:

- How CNN works for image classification.
- How to load and explore an image dataset.
- How image preprocessing works.
- How to train and evaluate a deep learning model.
- How data augmentation, dropout, and class weighting affect model performance.
- How to analyze model errors using a confusion matrix.

## 👩‍💻 Project Type

Deep Learning | Computer Vision | Image Classification

---

**Note:** This is an educational project developed to understand CNN-based traffic sign recognition and image classification.
