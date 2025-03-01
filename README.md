# **Heal AI: Wound Diagnosis and Prognosis Assistant**  

<img src="https://github.com/user-attachments/assets/21b320ea-a816-4c52-b953-5a1970c36a09" alt="Heal AI Banner" width="700"/>  

## Video Demonstrations:

- Demo on a Laptop [Click here](https://github.com/user-attachments/assets/16bb879a-b5f4-4972-a648-6338a865ea6c)

- Demo on a Mobile Phone [Click here](https://github.com/user-attachments/assets/7b70a8ac-3e97-40f3-8b2d-0a85c4bfc2f1)


### Submission to **Intel AI Hackathon** at **IEEE INDICON 2024**  

---

## **Team Name:** IntelMed  
### **Team Members:**  
- **Puspamita Banerjee**  
- **Swetha A**  
- **Arita Halder**  

---

## **Overview**  
Wound healing prognosis remains a critical challenge, with delays in detection often leading to severe complications. **Heal AI** addresses this issue through an AI-driven solution that combines a **web application** with a **diagnostic algorithm** for wound segmentation and classification.

### **Key Features:**  
- **DeepLabv3 Model**: Powered by a ResNet-50 backbone for image processing and segmentation.  
- **Classification**: Identifies wounds as **healthy**, **infected**, or **ischemic**.  
- **Color Analysis**: Enhances diagnostic accuracy.  
- **Accessibility**: Designed to empower caregivers with early detection tools, especially in underserved communities.  
- **Scalability**: Seamlessly integrates into healthcare systems with affordability and ease of deployment.  

---

## **Model Architecture**  
<img src="https://github.com/user-attachments/assets/66fc4ca5-5677-4fe0-916f-c277cd1311b0" alt="Model Architecture" width="600"/>  

---

## **Intel Technologies Used**  
<img src="https://github.com/user-attachments/assets/d6b1fee7-648f-4d8a-86a3-c66a98adf85b" alt="Intel Technology" width="600"/>  


---

## **Dataset**  
The model was trained on the [Wound Segmentation Dataset](https://www.kaggle.com/datasets/leoscode/wound-segmentation-images/data).  

---

## **Repository Features**  

This repository contains all the necessary codes and resources to reproduce our results.  

### **Web Applications:**  
1. **wound_app_tf**  
   - Runs the TensorFlow-based model.  
2. **wound_app_ov**  
   - Utilizes OpenVINO-optimized model for execution on Intel hardware.
  
### **Python Notebooks:**  
1. **wound_model.ipynb**  
   - Contains the codes for training the ResNet50-Deeplabv3+ model.  
2. **wound_coloranalysis.ipynb**  
   - Contains the codes for performing kmeans clustering and classification of the wounds.  

---

