# 🎙️ Hindi Audio Sentiment Analysis Using Machine Learning and Deep Learning  

## 📌 Project Overview  
This project presents an end-to-end Hindi audio sentiment analysis system developed during an academic research internship. The framework processes raw speech signals, performs advanced preprocessing, extracts acoustic features, and applies both Machine Learning and Deep Learning models for emotion classification.

The study evaluates multiple architectures to analyze performance improvements achieved through feature engineering and data augmentation.

---

## 🎯 Objectives  
• Develop a robust Hindi speech-based sentiment classification system  
• Perform advanced preprocessing and extract MFCC & Mel-Spectrogram features  
• Implement and compare Machine Learning and Deep Learning models  
• Improve model accuracy using augmentation and optimization techniques  

---

## 📊 Dataset  
• ~3000 Hindi audio recordings  
• Organized by actors, sessions, and emotion categories  
• Emotions: anger, disgust, fear, happy, neutral, sad, sarcastic, surprise  
• Multi-session structured dataset for robust training  

---

## 🛠️ Preprocessing & Feature Engineering  
• Noise reduction  
• Silence removal  
• Audio normalization  
• MFCC feature extraction  
• Mel-Spectrogram generation  
• Voice modulation-based data augmentation  
• Dataset balancing and scaling  

---

## 🧠 Models Implemented  

### 🔹 Machine Learning Models  
• Logistic Regression  
• Support Vector Machine (SVM)  
• Random Forest  
• K-Nearest Neighbors (KNN)  
• Voting Classifier  
• Stacking Classifier  

### 🔹 Deep Learning Models  
• CNN (Convolutional Neural Network)  
• CNN-LSTM Hybrid Model  
• Multi-Input CNN  
• MobileNet  
• EfficientNet  
• Hybrid MobileNet-EfficientNet Model  
• Multi-Input MobileNet  

---

## 📈 Evaluation Metrics  
• Accuracy  
• Precision  
• Recall  
• F1-Score  
• Confusion Matrix  

The optimized MobileNet-based model with augmented data achieved the best overall performance (≈82.89% accuracy), outperforming baseline ML models.

---

## 🚀 Tech Stack  
• Python  
• Librosa  
• NumPy, Pandas  
• TensorFlow / Keras  
• Scikit-learn  
• Matplotlib, Seaborn  
• Google Colab  

---

## 📌 Conclusion  
The project demonstrates that structured preprocessing, MFCC-based feature extraction, and deep learning architectures significantly enhance Hindi speech emotion recognition. Comparative analysis shows that transfer learning models like MobileNet deliver superior performance for scalable audio-based sentiment classification.
