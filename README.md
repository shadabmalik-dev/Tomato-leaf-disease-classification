Tomato Disease Detection using EfficientNetB0

Overview

This project focuses on detecting tomato leaf diseases using deep learning and transfer learning techniques. The model is trained on tomato leaf images to classify different disease categories and healthy leaves. EfficientNetB0 is used as the base architecture because of its strong image classification performance and lightweight design.

Features

- Tomato leaf disease classification
- EfficientNetB0 transfer learning
- Image preprocessing and augmentation
- Multi-class classification
- Performance evaluation using accuracy, precision, recall, and F1-score
- Confusion matrix visualization
- Fine-tuning support
- Prediction function for testing custom images

Dataset

The dataset contains tomato leaf images divided into training, validation, and testing folders. Each class contains images of a specific tomato disease or healthy leaves.

Model Architecture

The model uses EfficientNetB0 as the pretrained backbone model with additional dense and dropout layers added for classification.

Training Pipeline

- Data preprocessing
- Data augmentation
- Transfer learning
- Model training
- Fine-tuning
- Evaluation on test dataset

Results

The model performance is evaluated using different classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

Confusion Matrix

A confusion matrix is generated after testing to analyze prediction performance for each disease class.

Installation

git clone https://github.com/Shadab malikdev/tomato-disease-detection-efficientnet.git

cd tomato-disease-detection-efficientnet

pip install -r requirements.txt

Usage

Train Model

python train.py

Test Prediction

python predict.py

Project Structure

tomato-disease-detection-efficientnet/
│
├── dataset/
├── models/
├── notebooks/
├── results/
├── src/
├── app/
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore

Future Improvements

- Streamlit web application
- TensorFlow Lite conversion
- Real-time disease detection
- Mobile deployment
- Grad-CAM visualization

Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

Author

Muhammad Shadab

License

This project is licensed under the MIT License.
