✍️ Handwritten Alphabet Recognition with CNN
🧾 Project Overview
This project implements a Convolutional Neural Network (CNN) using Keras to classify handwritten English alphabet characters (A–Z). The model is trained on the A–Z Handwritten Data dataset, which contains labeled grayscale images of handwritten characters.

The goal is to accurately recognize handwritten letters from image input, a key task in Optical Character Recognition (OCR) systems.

📁 Dataset Description
Source: Kaggle – A–Z Handwritten Data

Contains over 372,000 labeled character images (28x28 grayscale)

Each image is associated with a label from 0 to 25, where:

0 = A, 1 = B, ..., 25 = Z

🛠️ Technologies & Libraries
Python

NumPy, Pandas

Matplotlib, OpenCV

TensorFlow / Keras

scikit-learn

🧠 Model Architecture
Input: 28×28 grayscale images

Layers:

Conv2D + ReLU

MaxPooling2D

Dropout

Flatten

Dense (Fully Connected)

Loss Function: Categorical Crossentropy

Optimizer: Adam

Callbacks: EarlyStopping, ReduceLROnPlateau

📊 Results
The model achieves high training and test accuracy (>95%)

Confusion matrix and example predictions were used to validate model performance

Successfully identifies most letters with strong generalization
