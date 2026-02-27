🍇 Grape Leaves Multi-Class Classification
Transfer Learning Based Deep Learning System
🚀 Overview

This project presents a production-oriented deep learning system for multi-class classification of grape leaf conditions using Transfer Learning techniques.

The objective is to detect and classify different grape leaf categories based on image data using pre-trained convolutional neural networks such as ResNet50 and MobileNet.

The repository demonstrates a complete deep learning workflow including data preprocessing, augmentation, model training, evaluation, and model optimization.

🎯 Project Objectives

Build a robust image classification system

Apply Transfer Learning using state-of-the-art CNN architectures

Compare model performance across experiments

Improve accuracy using augmentation and hyperparameter tuning

Provide a reproducible deep learning pipeline

🧠 Methodology
1️⃣ Data Preparation

Image preprocessing

Resizing and normalization

Train / Validation / Test split

2️⃣ Data Augmentation

Horizontal & vertical flipping

Rotation

Brightness adjustment

Scaling

Augmentation strategies were adjusted according to the selected model architecture.

3️⃣ Model Architecture

The following models were implemented:

ResNet50 (Pre-trained)

MobileNet (Pre-trained)

Transfer learning was applied by freezing base layers and training custom classification heads.

📊 Model Performance

The trained models achieved competitive performance across evaluation datasets:

Training Accuracy: 97.6%

Validation Accuracy: 91.0%

Test Accuracy: 88.0%

Increasing the number of training epochs showed measurable performance improvements during experimentation.

📂 Project Structure
grape-leaves-transfer-learning/
│
├── MLutiClassification_GrapeLeaves.ipynb
├── checkpoints/
├── results/
├── README.md
└── requirements.txt
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone <your-repository-link>
cd grape-leaves-transfer-learning
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Notebook
jupyter notebook

Open the notebook file and execute the training pipeline.

🛠 Technology Stack

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Seaborn

OpenCV

💡 Engineering Highlights

Practical application of Transfer Learning

Comparative model experimentation

Structured training and evaluation pipeline

Visual performance analysis

Scalable architecture for deployment

🔮 Future Improvements

Hyperparameter tuning with grid search

Model ensembling

Deployment as REST API

Cloud deployment

Integration with real-time agricultural monitoring systems

👨‍💻 Author

Mostafa Sharqawy
AI Engineer | Deep Learning | Computer Vision | NLP
