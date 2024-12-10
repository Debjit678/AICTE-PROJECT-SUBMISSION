# AICTE-PROJECT-SUBMISSION
# 📷 **ML-Based Image Recognition System**

### 🔍 **Project Overview**
This project focuses on developing an **AI-powered Image Recognition System** using the **CIFAR-10 dataset**. The CIFAR-10 dataset is a collection of **60,000 color images** of size **32x32 pixels**, categorized into **10 distinct classes**. Out of the total images, **50,000 are used for training** the model, while **10,000 are used for testing** its performance.  

This project is part of an AICTE internship on **Artificial Intelligence (AI)** and aims to create a **Learning Management System (LMS)**. Upon successful completion, certifications from **AICTE, Microsoft, and SAP** will be awarded.  

---

## 📚 **Table of Contents**
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Conclusion](#conclusion)
- [Creator](#creator)

---

## 📦 **Dataset Description**
The **CIFAR-10 dataset** is a widely used dataset for image classification tasks.  
**Key Details:**
- **Number of Images**: 60,000  
- **Image Size**: 32x32 pixels (RGB)  
- **Number of Classes**: 10 (Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck)  
- **Training Images**: 50,000  
- **Test Images**: 10,000  

The dataset can be easily imported using the **Keras library** to streamline model development and testing.  

---

## 💻 **Technologies Used**
- **Programming Language**: Python  
- **Libraries & Frameworks**:  
  - **Keras** - For model building and training  
  - **TensorFlow** - As the backend for Keras  
  - **NumPy** - For numerical computations  
  - **Matplotlib & Seaborn** - For visualization of results  
  - **Pandas** - For data analysis and manipulation  

---

## 🔧 **Installation & Setup**
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/ml-image-recognition-system.git
   cd ml-image-recognition-system
   ```
## 🚀 **Usage**
1. **Load the CIFAR-10 Dataset** using Keras:  
   ```python
   from keras.datasets import cifar10

   (X_train, y_train), (X_test, y_test) = cifar10.load_data()
   ```
2. Preprocess the Data:
   
   * Normalize pixel values (0 to 1)
   
   *  Convert class labels to categorical format
   
3. Build and Train the Model:
   
   * Use a Convolutional Neural Network (CNN) to train the model.
   
   * Use evaluation metrics like accuracy to assess the model's performance.
   
4. Test the Model:
   
   * Evaluate the model on the 10,000 test images.


## 🧠 **Model Architecture**
The **ML-Based Image Recognition System** uses a **Convolutional Neural Network (CNN)**.  
**Architecture Details**:
- **Input Layer**: Image of size 32x32x3 (RGB)  
- **Convolutional Layers**: Extract essential features from images  
- **Pooling Layers**: Reduce spatial dimensions  
- **Fully Connected Layers**: Classify the images into 10 categories  
- **Activation Functions**: ReLU and Softmax are used at different stages

## 📈 **Results**
The following metrics are used to evaluate the model's performance:   
- **Test Accuracy**: Achieved 67.10%  

## 🔍 **Conclusion**
The **ML-Based Image Recognition System** successfully classifies images from the **CIFAR-10 dataset**. The use of a **CNN architecture** allows the system to identify 10 different object categories with high accuracy. This project demonstrates essential AI/ML concepts like data preprocessing, model training, and evaluation.  

This project is part of an AICTE internship on AI, and successful completion will result in certifications from **AICTE, Microsoft, and SAP**.  

## ✍ **Creator**
**Name**: Debjit Mandal  
**Project Title**: ML-Based Image Recognition System  
**Mentorship**: AICTE Internship on AI  

