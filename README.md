🧠 Dementia Prediction Web Application

A Flask-based web application that predicts dementia using a hybrid machine learning approach by combining MRI image classification and clinical data analysis.

The system integrates a Convolutional Neural Network (CNN) for brain MRI image classification and a Support Vector Machine (SVM) model for structured patient data analysis. Based on both predictions, a final decision is generated to improve reliability and reduce misclassification.

🔍 Key Features

Secure user authentication using Flask sessions

MRI image preprocessing with OpenCV

Deep learning-based image classification (TensorFlow/Keras)

SVM-based clinical data prediction (Scikit-learn)

Hybrid decision logic combining both models

Automated PDF medical report generation using ReportLab

Clean web interface for data input and result visualization

🛠 Tech Stack

Python

Flask

TensorFlow / Keras

Scikit-learn

OpenCV

NumPy

ReportLab

📊 Prediction Classes

Non-Demented

Mild Demented

Very Mild Demented

Moderate Demented

📄 Output

Model-wise prediction results

Final diagnosis (Demented / Non-Demented / Further Test Recommended)

Downloadable professional medical report in PDF format
