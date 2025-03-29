# Rice-leaf-Disease-Prediction-System


---

## 🚀 Features

- ✅ Rice leaf disease classification using:
  - Support Vector Machine (SVM)
  - Random Forest
  - Custom Convolutional Neural Network (CNN)
  - MobileNetV2 (Transfer Learning)
- 📈 Model evaluation using accuracy, confusion matrix & classification report
- 🖼️ Image preprocessing using OpenCV & HOG
- 📄 Upload image or PDF for real-time prediction
- 📊 Skill analytics and results visualization
- 🌐 Interactive web interface built with Streamlit

---

## 🧪 Technologies Used

| Tech           | Purpose                        |
|----------------|--------------------------------|
| Python         | Core Programming Language      |
| scikit-learn   | ML Models (SVM, RF)            |
| TensorFlow     | CNN and MobileNetV2            |
| OpenCV         | Image Preprocessing            |
| Streamlit      | Web App Framework              |
| matplotlib     | Data Visualization             |
| PyPDF2         | PDF Extraction (Text/Image)    |

---

## 🧠 Models Overview

### 🔹 SVM & Random Forest
- Feature Extraction using HOG (Histogram of Oriented Gradients)
- Trained on preprocessed rice leaf images
- Output: Confusion matrix, accuracy, classification report

### 🔹 MobileNetV2
- Transfer learning using pre-trained weights
- Fine-tuned for rice leaf disease detection
- High accuracy with minimal training time

### 🔹 Custom CNN
- 5 convolutional layers + dropout + dense layers
- Achieved strong performance on test data
- Built from scratch using Keras/TensorFlow

---

## 📊 Model Performance

| Model            | Accuracy |
|------------------|----------|
| SVM              | ~85%     |
| Random Forest    | ~87%     |
| Custom CNN       | ~92%     |
| MobileNetV2      | ~95%     |

---

## 🧰 How to Run the Project

### 1. Clone this repo
```bash
git clone https://github.com/your-username/rice-leaf-disease-detection.git
cd rice-leaf-disease-detection
