# Bengali Handwritten Digit Recognition

> A Deep Learning project that recognizes handwritten Bengali digits (০–৯) using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

Handwritten digit recognition is one of the fundamental problems in computer vision and Optical Character Recognition (OCR). While significant progress has been made for Latin numerals, recognizing handwritten Bengali digits remains challenging due to the large variation in handwriting styles, curves, and stroke patterns.

This project presents a **Convolutional Neural Network (CNN)** based solution for recognizing handwritten Bengali digits (০–৯). The model was trained on a custom handwritten dataset collected from multiple volunteers and demonstrates the effectiveness of deep learning for Bengali numeral classification.

---

## ✨ Features

- Recognition of handwritten Bengali digits (০–৯)
- CNN-based deep learning model
- Image preprocessing pipeline
- Data normalization
- Model training using TensorFlow/Keras
- Model evaluation on unseen test data
- Suitable foundation for OCR applications

---

## 🗂 Dataset

A custom handwritten Bengali digit dataset was created for this project.

**Dataset Highlights**

- Approximately **900 handwritten digit images**
- Collected from **50+ volunteers**
- Covers Bengali numerals **০–৯**
- Multiple handwriting styles for improved diversity

Due to GitHub file size limitations, the dataset is hosted separately.

**Dataset Link**

👉 **https://drive.google.com/drive/u/0/folders/1tC_IGMMSHyZCTpPGZqZgYaBTa6Jx70oD**

---

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Model Workflow

```
Input Image
      │
      ▼
Image Preprocessing
(Grayscale → Resize → Normalize)
      │
      ▼
Convolutional Neural Network (CNN)
      │
      ▼
Feature Extraction
      │
      ▼
Classification
      │
      ▼
Predicted Bengali Digit
```

---

## 📁 Project Structure

```
bengali-handwritten-digit-recognition/
│
├── docs/
│   ├── Final_Report.pdf
│   └── Final_Presentation.pptx
│
├── notebook/
│   └── bengali_digit_recognition.ipynb
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/IvyKumbhakar/bengali-handwritten-digit-recognition.git
```

Move into the project directory

```bash
cd bengali-handwritten-digit-recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebook/bengali_digit_recognition.ipynb
```

Run all notebook cells sequentially.

---

## 📊 Results

The CNN model successfully learned meaningful handwritten digit features and achieved promising classification performance on the custom dataset.

**Highlights**

- Custom handwritten dataset
- TensorFlow/Keras implementation
- CNN architecture
- Approximately **91.8% test accuracy**
- Good generalization across different handwriting styles

---

## 🌍 Applications

This project can be extended for applications such as:

- OCR systems
- Bank cheque digit recognition
- Postal code recognition
- Automated form processing
- Educational assessment systems
- Historical document digitization

---

## 🔮 Future Improvements

- Increase dataset size
- Apply advanced data augmentation
- Experiment with ResNet and EfficientNet
- Deploy as a web application
- Mobile application integration
- Real-time handwritten digit recognition

---

## 👨‍💻 Author

**Ivy Kumbhakar**

Master of Computer Applications (MCA)  
University of Calcutta

GitHub: https://github.com/IvyKumbhakar

---

## 📄 Documentation

The complete project report and presentation are available in the **docs** directory.

- Final Project Report
- Final Project Presentation

---

## 📜 License

This project is licensed under the MIT License.

See the **LICENSE** file for more information.

---

### ⭐ If you found this project useful, consider giving it a star.
