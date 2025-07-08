# 😷 Face Mask Detection using MobileNetV2 + Softmax

This project uses MobileNetV2 with a softmax output layer to classify images as either WithMask or WithoutMask.

---

## 🔧 Key Details

- Output Layer: Dense(2, activation='softmax')
- Classification: Multiclass (WithMask = 0, WithoutMask = 1)
- Loss Function: Categorical Crossentropy
- Final Prediction: np.argmax on probabilities

---

## 📈 Performance

- Test Accuracy: 99.6%
- F1-Score: 1.00 (both classes)
- Epochs Trained: 10
- Used full dataset, early stopping, and checkpointing

---

## 📊 Visualizations

- Training and validation loss curve only (no accuracy plot)

---

## 🎥 Real-Time Webcam Prediction

- Real-time webcam detection included.
- Detects mask status and displays label on camera feed using OpenCV.
