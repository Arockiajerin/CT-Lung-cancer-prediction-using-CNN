# CT-Lung-cancer-prediction-using-CNN
  A deep learning-based system for detecting lung cancer from CT scan images using Convolutional Neural Networks (CNN) and Gradio for user interface.

## 🚀 Features:

- Deep Learning Model: CNN architecture for image classification
- Multi-class Classification: Detects different types of lung conditions
- Web Interface: User-friendly Gradio web app
- High Accuracy: Trained on 3003 medical images
- Real-time Prediction: Instant results with confidence scores

## 📁 Project Structure:
lung-cancer-detection/
├── lung_cancer_detection.ipynb     # Main Jupyter notebook
├── lung_cancer_cnn.h5              # Trained model
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
└── sample_images/                  # Sample CT scan images

##🛠️ Installation
###Prerequisites
- Python 3.8+
- Jupyter Notebook
- Google Colab (for running the notebook)
  
##📊 Dataset
The model is trained on a dataset containing 3003 lung CT scan images across three categories:
- lung_aca: Lung adenocarcinoma
- lung_scc: Lung squamous cell carcinoma
- lung_n: Normal lung (no cancer)

##Dataset Statistics:
- Total Images: 3003
- Training Set: 2402 images (80%)
- Testing Set: 601 images (20%)
- Image Size: 224x224 pixels (grayscale)

##⚠️ Important Notes
- Medical Disclaimer: This is a research project and should not be used for actual medical diagnosis
- Dataset Limitations: Model performance depends on training data quality and diversity
- Clinical Validation: Requires validation with clinical experts before real-world use
