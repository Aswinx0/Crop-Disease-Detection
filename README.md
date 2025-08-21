# Crop-Disease-Detection

🌱 Plant Disease Detection
An AI-powered system that accurately identifies diseases in various plants from leaf images using state-of-the-art Vision Transformer (ViT) models. Built to help farmers improve crop yield and manage plant health effectively.

🚀 Features
Multi-Model Architecture: Implements and compares various ViT models (ViT-B16, ViT-L16, ViT-S16, ViT-B32).

Multi-Plant Support: Designed to work with tomatoes, strawberries, apples, and more.

High Accuracy: Achieves over 93% accuracy on validation sets.

Data Augmentation: Enhanced training with rotation, flipping, and scaling.

Comprehensive Analysis: Includes confusion matrices, classification reports, and performance graphs.

🛠️ Tech Stack
Python

TensorFlow / Keras

TensorFlow Hub (for pre-trained ViT models)

Scikit-learn (for metrics)

OpenCV & PIL (for image processing)

Matplotlib & Seaborn (for visualization)

📁 Project Structure
text
├── notebooks/
│   └── Plant_Disease_Detection.ipynb  # Main training & analysis notebook
├── models/                             # Saved pre-trained models
├── data/                               # Dataset directory
├── results/                            # Output graphs & metrics
└── README.md
📊 Results
The ViT-B16 model achieved the following results on the PlantVillage dataset:

Model	Accuracy	Precision	Recall	F1-Score
ViT-B16	93.47%	0.94	0.93	0.93
Sample Confusion Matrix:
https://i.imgur.com/example-image.png

🏃‍♂️ Quick Start
The project is developed on Kaggle and uses the Plant Village Dataset.

Open on Kaggle: Link to your Kaggle Notebook

Run all cells to install dependencies, load data, train models, and view results.

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

💡 Note: This project was developed on Kaggle. For local execution, please ensure all dependencies from requirements.txt are installed.
