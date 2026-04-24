#  Plant Disease Detection System

##  Project Overview
This project is a **computer vision-based plant disease detection system** developed using deep learning. The system analyzes plant leaf images and classifies them into different disease categories or healthy conditions. It supports early diagnosis and can assist farmers and researchers in improving crop health.

---

##  Aim
To develop an AI-based system that can automatically detect plant diseases from leaf images using deep learning techniques.

---

## Features
- Multi-class plant disease classification  
- High accuracy using deep learning (MobileNetV2)  
- Upload image and get instant prediction  
- Displays confidence score  
- Lightweight and efficient model  

---

## Technologies Used
- Python  
- Google Colab  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## Dataset
The dataset contains plant leaf images of multiple crops including:
- Tomato  
- Potato  
- Apple  
- Corn  
- Pepper  

Each folder represents a class (disease or healthy condition).


---

##  System Architecture

User Image → Preprocessing → Deep Learning Model → Prediction → Output


---

## Model Details
- Model: MobileNetV2 (Transfer Learning)  
- Input size: 224 × 224  
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  

---

## How It Works
1. User uploads a plant leaf image  
2. Image is resized and preprocessed  
3. Model predicts disease class  
4. Output shows:
   - Predicted disease  
   - Confidence score  

---

## How to Run

### Option 1: Google Colab
1. Open the notebook  
2. Mount Google Drive  
3. Load trained model  
4. Upload image  
5. Run prediction  

### Option 2: Local Setup
pip install -r requirements.txt
python predict.py

---

## Results
The model successfully classifies plant diseases with high accuracy on validation data.


---

## ⚠️ Challenges
- Similar disease patterns  
- Dataset imbalance  
- Image quality variations  

---

## Future Improvements
- Real-time detection using camera  
- Mobile app deployment  
- Larger and more diverse dataset  
- Advanced models like EfficientNet  

---

--

## 👨‍💻 Author
Shrean

---

## 📚 References
- Géron, A. (2019) Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow  
- TensorFlow Documentation: https://www.tensorflow.org  
- PlantVillage Dataset: https://www.kaggle.com/datasets/emmarex/plantdisease  

---
