# 😷 Face Mask Detection using MobileNetV2 + Sigmoid

This project implements a binary classifier to detect if a person is wearing a face mask using transfer learning with MobileNetV2.

---

## 🔧 Key Details

- Output Layer: Dense(1, activation='sigmoid')
- Classification: Binary (0 = WithMask, 1 = WithoutMask)
- Loss Function: Binary Crossentropy
- Final Activation Threshold: 0.5

---

## 📈 Performance

- Test Accuracy: 98.9%
- F1-Score: 0.99 (both classes)
- Epochs Trained: 12
- EarlyStopping and ModelCheckpoint used

---

## 📊 Visualizations

- Training and validation accuracy/loss curves
- Classification report with precision, recall, F1-score

---

## 🎥 Real-Time Webcam Prediction

- OpenCV script included at the end of the notebook.
- Predicts from webcam in real-time and overlays the label on the video feed.
