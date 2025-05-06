
# DS4002-CS3-Case-Study-ASL-Digits

**CS3 Case Study Repository – Paul Rosa**

## Recognizing ASL Digit Signs from Images

---

### **Contents of this Repository**

This repository is designed as a **case study challenge** to help students build and evaluate a Convolutional Neural Network (CNN) that can classify American Sign Language (ASL) digit signs (0–9) from static images. It contains all the materials you’ll need to step into the shoes of a machine learning engineer and complete the project.

---

## **1. Software and Platform**

- **Language:** Python  
- **Packages Required:**  
  - `tensorflow`  
  - `numpy`  
  - `matplotlib`  
  - `sklearn`  
  - `keras`  
  - `glob`  
  - `os`
- **Platform:** Google Colab (recommended), Windows/macOS/Linux

---

## **2. Repository Map**

📂 **Root Directory**  
- `README.md` → This documentation file  
- `LICENSE.md` → MIT License  

📂 **Hook_Document/**  
- `Hook_Document.pdf` → One-page intro to the case study

📂 **Rubric/**  
- `Rubric.pdf` → Detailed rubric for the case study deliverables

📂 **Materials/**  
- `ASL_Digit_CNN_Analysis.ipynb` → Main Colab notebook with all steps  
- `model_accuracy_plot.png` → Training and validation accuracy graph  
- `confusion_matrix.png` → Confusion matrix visual  
- `classification_report.pdf` → Model performance summary  
- `asl_digit_model.h5` → Saved CNN model weights  
- `asl_data_link.txt` → Link to the ASL digit dataset

---

## **3. How to Get Started**

> This case study will walk you through building, training, and evaluating a CNN model that predicts ASL digit signs from static images.

**Steps:**

1. **Read the Hook Document:** Start with `Hook_Document.pdf` to understand the mission and high-level goals.
2. **Review the Rubric:** Check `Rubric.pdf` for detailed instructions and grading criteria.
3. **Prepare the Data:** Make sure you have the ASL digit dataset saved to your Google Drive at:  
   `/MyDrive/Sign-Language-Digits-Dataset/Dataset/` with subfolders `0` to `9`.
4. **Run the Notebook:** Open `ASL_Digit_CNN_Analysis.ipynb` in Google Colab and run each cell in order.
5. **Submit Your Work:** Follow the rubric to complete your notebook, report, and model evaluation.

---

## **4. Citations**

**Data Source:**  
- https://github.com/ardamavi/Sign-Language-Digits-Dataset

**Tools & References:**  
- TensorFlow + Keras Documentation  
- Google Colab Documentation  
- IEEE Citation Style Guide  
- Blog Post Explainers (see `Materials/` folder)

---

## **5. Project Overview**

In this case study, you’ll work with a dataset of ASL digit images (~2,000 samples) and build a CNN to classify hand signs from 0 to 9. The dataset is organized into labeled folders, and you’ll walk through all key steps of a data science project:

- **Loading and preprocessing the data**
- **Building and training a CNN model**
- **Evaluating performance with accuracy, confusion matrices, and more**
- **Reflecting on model strengths and areas for improvement**

By the end, you’ll have a solid understanding of how machine learning can be applied to real-world accessibility problems—and how to document your work like a pro.

---

**Created by Paul Rosa – DS 4002 (Spring 2024)**
