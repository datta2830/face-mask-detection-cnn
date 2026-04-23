# face-mask-detection-cnn
Deep learning project using CNN to detect face masks in real-time with OpenCV and Streamlit



# 😷 Face Mask Detection using CNN

![Python](https://img.shields.io/badge/Python-3.8-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

This project is a deep learning-based system that detects whether a person is wearing a face mask or not using a Convolutional Neural Network (CNN).

It can be used in real-world applications like:

* Public places (airports, malls, hospitals)
* Safety monitoring systems
* Smart surveillance

---

## 📦 Dataset

* Dataset contains images of:

  * 😷 With Mask
  * ❌ Without Mask
* Images are preprocessed and resized before training

*(Tip: Add dataset link here if from Kaggle)*

---

## 🧠 Model Architecture

The CNN model consists of:

* Convolutional layers (feature extraction)
* MaxPooling layers (downsampling)
* Fully connected layers
* Softmax output (classification)

---

## 📊 Results

* Model Accuracy: **(Add your actual accuracy here)**
* Loss: **(Add value)**

---

## 📂 Project Structure

```id="9kym25"
face-mask-detection-cnn/
│── face-mask-detection.ipynb
│── app.py
│── model/
│── requirements.txt
│── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

```id="a8u2wx"
git clone https://github.com/datta2830/face-mask-detection-cnn.git
cd face-mask-detection-cnn
```

### 2️⃣ Install Dependencies

```id="yr68z4"
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```id="dhslru"
python app.py
```

---

## 💻 Usage

You can:

* Run model on images
* Detect faces using OpenCV
* Classify mask / no-mask

---

## 🌐 Web App (Optional)

This project can be extended using **Streamlit** to create a simple web interface.

---

## 🔬 Real-World Testing

* Works well on clear frontal faces
* Sometimes misclassifies:

  * Beards as masks
  * Low-light images

---

## ⚠️ Limitations

* Limited dataset size
* Not robust in extreme lighting conditions
* Accuracy may drop for side faces

---

## 🔮 Future Improvements

* Use larger and diverse dataset
* Implement transfer learning (ResNet, MobileNet)
* Deploy using cloud (AWS / GCP)
* Mobile app integration

---

## 👨‍💻 Author

**Datta Biradar**
Final Year AIML Student

---

## 📜 License

This project is licensed under the MIT License.
