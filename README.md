# **Diabetic Retinopathy Detection using ResNet18** 
.

## **Overview**  
This project focuses on detecting **Diabetic Retinopathy (DR)** from retinal images using **deep learning** techniques. We leveraged the **ResNet18** architecture to build an advanced **image classification model**, aiding in early diagnosis and treatment. The model was trained on a dataset of **20,000+ retinal images** and achieved an accuracy of **96%** through extensive fine-tuning and validation.  

## **Technologies Used**  
- **Python**  
- **Machine Learning (Deep Learning - ResNet18)**  
- **OpenCV**  
- **Flask (for API deployment)**  

## **Features**  
- **ResNet18-based model** for efficient retinal image classification.  
- **Preprocessing** of retinal images using OpenCV.  
- **Flask API** for deploying and testing the model.  
- **Fine-tuned model achieving 96% accuracy.**  

## **Installation & Setup**  
### **Clone the Repository**  
```bash
git clone https://github.com/your-username/diabetic-retinopathy-detection.git
cd diabetic-retinopathy-detection
```

### **Create Virtual Environment & Install Dependencies**  
```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows
pip install -r requirements.txt
```

### **Run the Flask Application**  
```bash
python app.py
```

## **Dataset**  
The model is trained on a dataset of **20,000+ retinal images**, preprocessed for optimal accuracy.  
(Dataset source: [https://www.kaggle.com/datasets/mariaherrerot/aptos2019])  

## **Usage**  
- Upload a **retinal image** through the web interface or API.  
- The model predicts the **Diabetic Retinopathy stage** (No DR, Mild, Moderate, Severe, Proliferative).  
- Outputs the **prediction results with confidence scores**.  

## **Results**  
- **Accuracy:** 96%  
- **Loss Optimization:** Fine-tuned using **data augmentation** and **hyperparameter tuning**.  

## **Contributors**  
- **[Mahesh Bodkhe]** (Team Lead)  
- **[Geeta Patil]**
- **[Abhishek Bodkhe]**  

## **License**  
This project is licensed under the **MIT License**.  

----
