# PRODIGY_ML_04
🖐️ Hand Gesture Recognition using Machine Learning
📌 Project Overview

This project implements a Hand Gesture Recognition system using Machine Learning techniques.
The model classifies different hand gestures from images by extracting meaningful features and applying a supervised learning algorithm.

Unlike deep learning approaches, this project follows a classical machine learning pipeline using feature engineering and SVM, making it lightweight and easy to understand.

🎯 Objective

To build a machine learning model that can:

Recognize hand gestures from image data

Classify gestures accurately

Enable intuitive human–computer interaction

🛠️ Technologies Used

Python

OpenCV – image processing

NumPy – numerical computations

scikit-image – HOG feature extraction

scikit-learn – SVM classifier & evaluation

Matplotlib – visualization

📂 Dataset

Leap Gesture Recognition Dataset
Source: Kaggle

🔗 https://www.kaggle.com/datasets/gti-upm/leapgestrecog

Dataset Structure
leapGestRecog/
 ├── 00/
 │    ├── 01_palm/
 │    ├── 02_l/
 │    ├── 03_fist/
 │    └── ...
 ├── 01/
 ├── 02/
 └── ...


Each folder represents a different user

Each subfolder represents a gesture class

🧠 Methodology

Image Preprocessing

Convert images to grayscale

Resize images to 64×64

Feature Extraction

Histogram of Oriented Gradients (HOG) is used to extract shape and edge features

Model Training

Support Vector Machine (SVM) with RBF kernel is trained on extracted features

Evaluation

Accuracy score

Precision, Recall, F1-score

Prediction

Model predicts the gesture for unseen images, including custom user images

🔁 Workflow
Input Image → Preprocessing → HOG Feature Extraction → SVM Classifier → Gesture Output

📊 Results

Achieved high accuracy on the test dataset

Successfully predicts gestures from new and custom images

Robust and efficient for classical ML-based image classification

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/hand-gesture-recognition-ml.git

2️⃣ Install Required Libraries
pip install opencv-python numpy scikit-learn scikit-image matplotlib

3️⃣ Download the Dataset

Download from Kaggle

Extract the folder leapGestRecog

Place it in the project directory or update the dataset path in the code

4️⃣ Run the Code

Open the Jupyter Notebook or Python file and run all cells.

🧪 Testing with Custom Images

You can test the model using your own hand gesture images by providing the image path to the prediction function.
The same preprocessing and feature extraction steps are applied before prediction.

🏆 Key Highlights

✅ Pure Machine Learning approach

✅ No deep learning or CNN used

✅ Feature engineering with HOG

✅ Suitable for academic and internship submissions

✅ Lightweight and easy to understand
