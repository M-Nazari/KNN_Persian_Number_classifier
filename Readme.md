🔢 Persian Handwritten Digit Recognition using K-Nearest Neighbors (KNN)
📘 Project Overview

This project implements a machine learning model to recognize Persian handwritten digits (0–9) using the K-Nearest Neighbors (KNN) algorithm.
The model is trained and tested on the Hoda dataset, a large collection of handwritten Persian digits gathered by Tarbiat Modares University (TMU), Iran.
The project is developed in Google Colab using Python and standard machine learning libraries.

🎯 Objective

To build an accurate classifier that can automatically detect and classify Persian handwritten digits by analyzing pixel-based image features.

🧠 Methodology

Dataset:

The Hoda dataset contains thousands of Persian handwritten digits (0–9) collected from real-world samples.

Each image is preprocessed and converted into grayscale pixel arrays.

Model:

Algorithm: K-Nearest Neighbors (KNN)

Implemented using scikit-learn

Tuned for optimal k value to balance bias and variance.

Steps Performed:

Data loading and preprocessing

Feature scaling and normalization

Splitting data into training and testing sets

Training and evaluating the KNN model

Measuring accuracy and performance metrics

📊 Results

The trained model achieved high accuracy in classifying Persian digits (0–9).

Demonstrated effectiveness of the KNN algorithm for Persian OCR (Optical Character Recognition) tasks.

🧰 Technologies Used

Python

NumPy, Pandas

scikit-learn (KNN Classifier)

Matplotlib (for visualization)

Google Colab

📂 Repository Structure
KNN_Persian_Number_Classification/
│
├── KNN_Persian_Number_Classification.ipynb   # Google Colab notebook with code
├── README.md                                # Project documentation
└── (optional) /data                         # Folder for dataset (if used locally)


🚀 Future Work

Compare KNN results with CNN-based deep learning models.

Expand dataset for more handwriting styles.

Deploy the model as a simple web app for digit recognition.

👩‍💻 Author

Mahjoobe Nazari
Data Science & AI Enthusiast
LinkedIn
GitHub