# 🎙️ Hindi Audio Sentiment Analysis Using Machine Learning and Deep Learning  

## 📌 Project Overview  
This project builds an end-to-end Hindi audio sentiment analysis system to classify emotions from speech signals. The framework processes raw audio, performs preprocessing, extracts acoustic features, and applies both Machine Learning and Deep Learning models for accurate emotion classification.

## 🎯 Objectives  
• Develop a Hindi speech-based sentiment classification system  
• Perform preprocessing and extract MFCC & Mel-Spectrogram features  
• Implement and compare ML and DL models  
• Improve accuracy using data augmentation and model optimization  

## 📊 Dataset  
• ~3000 Hindi audio recordings  
• Organized by actors and sessions  
• 8 emotion categories (anger, happy, sad, neutral, fear, surprise, disgust, sarcastic)  
• Structured multi-session dataset  

## 🛠️ Preprocessing  
• Noise reduction  
• Silence removal  
• Audio normalization  
• MFCC feature extraction  
• Mel-Spectrogram generation  
• Data augmentation (noise, pitch shift, time stretch)  
• Feature scaling and dataset balancing  

## 🤖 Models Implemented  

### Machine Learning  
• Logistic Regression  
• Support Vector Machine (SVM)  
• Random Forest  
• K-Nearest Neighbors (KNN)  
• Voting Classifier  
• Stacking Classifier  

### Deep Learning  
• CNN  
• CNN-LSTM  
• Multi-Input CNN  
• MobileNet  
• EfficientNet  
• Hybrid MobileNet-EfficientNet  
• Multi-Input MobileNet  

## 📈 Evaluation  
• Accuracy  
• Precision  
• Recall  
• F1-Score  
• Confusion Matrix  

The optimized MobileNet-based model with augmented data achieved the best performance (~82.89% accuracy).

## 🚀 Tech Stack  
• Python  
• Librosa  
• NumPy, Pandas  
• Scikit-learn  
• TensorFlow / Keras  
• Matplotlib, Seaborn  
• Google Colab  

## 📌 Conclusion  
The project demonstrates that structured preprocessing, MFCC-based feature extraction, and transfer learning models significantly improve Hindi speech emotion recognition, providing a scalable solution for audio-based sentiment analysis.
