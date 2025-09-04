# Hand_written_digit_recognition_knn_ML_model


This project focuses on recognizing handwritten digits using the **MNIST dataset** and the **K-Nearest Neighbors (KNN)** algorithm.  
The goal is to classify digits (0–9) based on grayscale images and test the model with both standard MNIST data and self-created handwritten samples.

---

## 📂 Dataset
- **MNIST Dataset**:  
  - 60,000 training images  
  - 10,000 testing images  
  - Each image is a 28×28 grayscale matrix representing digits from 0 to 9.  

---

## ⚙️ Project Workflow
1. **Import Libraries and Load Data**  
   - Used `keras.datasets.mnist` for loading MNIST.  

2. **Preprocessing**  
   - Flattened images from (28×28) to (784) dimensions.  
   - Normalized pixel values for better performance.  

3. **Model Implementation**  
   - Applied **KNN Classifier** for digit classification.  
   - Trained and evaluated on MNIST dataset.  

4. **Evaluation**  
   - Achieved **97.05% accuracy** on test data.  

5. **Real-world Testing**  
   - Wrote digits on paper ✍️  
   - Captured them with phone camera 📱  
   - Preprocessed images and tested on the trained model  
   - Model correctly predicted the handwritten digits ✅  

---

## 📊 Results
- Test Accuracy on MNIST: **97.05%**  
- Custom handwritten digits were also predicted correctly by the model.  

Example Results (Self-created handwritten digits):  

| Input Image | Predicted Digit |
|-------------|-----------------|
| ![digit1](images/digit1.png) | 5 |
| ![digit2](images/digit2.png) | 9 |
| ![digit3](images/digit3.png) | 2 |
| ![digit4](images/digit4.png) | 7 |

---

## 🚀 Key Learnings
- Data preprocessing and reshaping image matrices for ML models  
- Implementing **KNN** for image classification  
- Evaluating with standard datasets and **validating using real-world samples**  
- Gained deeper insight into supervised learning and image recognition  

---

## 🛠️ Tech Stack
- Python 🐍  
- NumPy  
- Matplotlib  
- OpenCV  
- Scikit-learn  

---

## 📌 Future Work
- Implementing **Convolutional Neural Networks (CNNs)** for improved accuracy  
- Building a web-based or mobile app interface for digit recognition  

---

## 📷 Screenshots
(Add screenshots of training results, accuracy plots, and handwritten digit predictions here)

---

## 🔗 GitHub & LinkedIn
- GitHub Repo: [Your Repo Link]  
- LinkedIn Post: [Your LinkedIn Link]  

---

⭐ If you found this project helpful, don't forget to give it a star!

