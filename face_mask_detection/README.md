# 😷 Face Mask Detection using CNN

This project demonstrates the use of a **Convolutional Neural Network (CNN)** to detect whether a person is wearing a face mask or not. It is built using **Python**, **Keras**, and **TensorFlow**, and is trained on a dataset of images classified into two categories: **"With Mask"** and **"Without Mask"**.

---

## 📁 Project Structure

```
Face_mask_detection_using_CNN/
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

## 🚀 Features

* Binary image classification (Mask vs No Mask)
* Simple CNN model with Conv2D, MaxPooling2D, Flatten, Dense layers
* Real-time predictions using the trained model (future enhancement)
* Training visualization with accuracy/loss graphs

---

## 📦 Requirements

Install the following dependencies before running the notebook:

```bash
pip install tensorflow keras matplotlib numpy opencv-python scikit-learn
```

---

## 🧠 Model Architecture

* **Input Layer:** Resized image (150x150x3)
* **Conv2D + MaxPooling**
* **Flatten**
* **Dense Layers**
* **Output Layer:** Sigmoid activation (binary classification)

---

## 🧪 Dataset

The dataset is organized into two folders:

* `with_mask/`: Contains images of people wearing face masks
* `without_mask/`: Contains images of people not wearing face masks

Ensure the dataset is preprocessed and split properly for training and validation.

---

## 📈 Training Output

* **Accuracy and Loss Curves** saved as `accuracy.png` and `loss.png` in the `plots/` directory.
* **Model** saved as `mask_detector.model` in the `model/` directory.

---

## 🧾 How to Use

1. Clone the repository:

```bash
git clone https://github.com/SAMUDRAGUPTA002/face-mask-detection-cnn.git
cd face-mask-detection-cnn
```

2. Run the notebook:
   Open `Face_mask_detection_using_CNN.ipynb` in Jupyter Notebook or VSCode and run all cells to train and evaluate the model.

3. (Optional) Use the model for real-time prediction:
   You can load `mask_detector.model` and use OpenCV to perform webcam-based predictions.

---

## 📊 Results

The model achieves high accuracy (\~97% on training and \~96% on validation). Below are sample output plots:

* **Training Accuracy:**
  ![Accuracy](plots/accuracy.png)

* **Training Loss:**
  ![Loss](plots/loss.png)

---

## 📌 Future Work

* Add webcam support for live mask detection
* Improve model accuracy with data augmentation
* Deploy using Flask/Streamlit for browser-based inference

---

## 📜 License

This project is licensed under the **MIT License**.


