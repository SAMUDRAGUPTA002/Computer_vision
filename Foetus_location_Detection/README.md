# 🧬 Fetus Organ Location Detection with EDA & YOLO

This project involves identifying fetal organ locations using a combination of **Exploratory Data Analysis (EDA)** and **YOLO (You Only Look Once)** object detection techniques. The analysis aims to understand the spatial distribution of organs and apply deep learning for precise localization.

## 📊 Features

* 🔍 Exploratory Data Analysis on fetal imaging dataset.
* 🧠 Object detection using YOLOv5 or YOLOv8 (based on your implementation).
* 🖼️ Bounding box visualization on fetal ultrasound images.
* 📌 Accurate organ location detection using pretrained/custom YOLO model.

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **YOLOv5 / YOLOv8** (via `ultralytics` or `torch.hub`)
* **OpenCV**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn**

## ▶️ How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SAMUDRAGUPTA002/Computer_vision/tree/c3def2b9066d14cd8dead5aab41a3fc534bc143e/Foetus_location_Detection
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run YOLO detection:**

   * If using YOLOv5:

     ```bash
     git clone https://github.com/ultralytics/yolov5
     cd yolov5
     pip install -r requirements.txt
     python detect.py --weights path/to/weights.pt --source path/to/images
     ```

   * If using YOLOv8 (`ultralytics` package):

     ```bash
     pip install ultralytics
     yolo task=detect mode=predict model=path/to/model.pt source=path/to/images
     ```

4. **Run the EDA notebook:**

   ```bash
   jupyter notebook
   # Open 'fetus_organ_location with EDA.ipynb'
   ```

## 📂 File Structure

```
fetus_organ_location with EDA.ipynb   # EDA and data visualization
yolo/                                 # YOLO training or inference scripts
models/                               # YOLO trained weights
images/                               # Test images for detection
README.md                             # Project documentation
requirements.txt                      # Required Python packages
```

## 📄 License

This project is licensed under the **MIT License**.

