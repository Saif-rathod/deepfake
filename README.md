
# 🕵️‍♂️ Deepfake Detection: Temporal & Spatial Inconsistencies Analysis  

An advanced deep learning approach to detect deepfake videos by analyzing both temporal (frame-to-frame inconsistencies) and spatial (within-frame artifacts) features.

🚀 Project Overview
Deepfake videos pose a serious threat to digital media. This project leverages deep learning architectures to detect inconsistencies in videos, ensuring better authenticity verification.

📌 Celeb-DF (v2) Dataset Overview
Celeb-DF (v2) is a large-scale deepfake dataset specifically created to improve the generalization ability of deepfake detection models. It contains high-quality fake videos generated with improved deepfake synthesis techniques.

## Key Features of Celeb-DF (v2)
✅ Total Videos: 590 real & 5,639 deepfake videos
✅ High Resolution: More realistic fake videos compared to earlier datasets
✅ Better Lip Synchronization: Improved lip motion for fake videos

## 🚀 Features  
✔ Detects deepfake inconsistencies using **CNNs & RNNs**  
✔ Temporal & spatial analysis for **better accuracy**  
✔ Trained with **ResNet-50 & LSTMs**  
✔ Evaluated using **K-Fold Cross Validation**  

🏗 Architectural Design
📌 Models Used
Model	Purpose
ResNet-50	Feature extraction from frames
LSTM	Temporal sequence analysis
CNN-Based Networks	Spatial artifact detection

🧠 Training Details
Loss Function: Binary Cross-Entropy (BCELoss)
Optimizer: AdamW (lr=0.0001)
Validation: K-Fold Cross Validation
Hardware: Trained on CUDA GPU (if available)

## 📊 Training & Evaluation  
- Loss function: **Binary Cross-Entropy (BCELoss)**  
- Optimizer: **AdamW**  
- K-Fold Cross Validation for better generalization  


## 📜 License  
MIT License  
wait for it lol.
---

This keeps it **minimal, clean, and structured** while highlighting key aspects. Let me know if you need further refinements! 🚀
