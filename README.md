# 🧠 SCT_ML_4 - ASL Hand Gesture Recognition

This project implements a CNN model to recognize American Sign Language (ASL) hand gestures from images.

## 📁 Dataset
- Source: [Kaggle - ASL Hand Gesture Train Dataset](https://www.kaggle.com/datasets/shaurayavohra/asl-hand-gesture-train-dataset)
- Contains 29 gesture classes (A-Z, SPACE, DELETE, NOTHING)

## 🧪 Model
- Framework: TensorFlow/Keras
- Architecture: 2 Conv2D layers → Flatten → Dense → Dropout
- Accuracy: *~96% on training, ~93% on validation*



![Model Accuracy & Loss](model_accuracy_loss.png)

![Confusion Matrix](confusion_matrix.png)


![Predicted vs Actual](predicted_vs_actual.png)

