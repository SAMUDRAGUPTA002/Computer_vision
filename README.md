# Computer_vision

# 😷 Face Mask Detection using CNN

This project uses a **Convolutional Neural Network (CNN)** to detect whether a person is **wearing a mask or not**, using image classification.

---

## 📁 Structure

```
├── Face_mask_detection_using_CNN.ipynb
├── dataset/
│   ├── with_mask/
│   └── without_mask/
├── model/
│   └── mask_detector.model
├── plots/
│   ├── accuracy.png
│   └── loss.png
```

---

## 🛠 Requirements

```bash
pip install tensorflow keras numpy matplotlib opencv-python scikit-learn
```

---

## 🧠 Model Summary

* Input: 150x150 RGB images
* Layers: Conv2D → MaxPool → Flatten → Dense
* Output: Sigmoid (Mask / No Mask)

---

## 📊 Results

* Accuracy \~96% on validation set
* Model saved as `mask_detector.model`
* Training plots in `plots/` folder

---

## ▶️ Run

1. Open `Face_mask_detection_using_CNN.ipynb`
2. Run all cells to train and test the model

---

## 🚀 Future Scope

* Real-time mask detection using webcam
* Web app with Flask or Streamlit

---

## 📄 License

MIT License

