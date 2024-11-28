
https://github.com/user-attachments/assets/58c3c74c-aac7-4d38-a972-8c4a959d03f6

# **Sign Language Recognition System** 🖐️🤖  


### **Table of Contents**
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Project Workflow](#project-workflow)  
7. [Results](#results)  
8. [Future Scope](#future-scope)  
9. [License](#license)  
10. [Acknowledgments](#acknowledgments)  

---

## **Introduction**  
The **Sign Language Recognition System** is an AI-powered solution designed to interpret sign language gestures into readable text in real time. It aims to bridge the communication gap between individuals with hearing or speech impairments and the rest of the world.  

---

## **Features**  
- Real-time recognition of hand gestures using webcam input.  
- Accurate detection of hand landmarks with **Mediapipe**.  
- Classification of gestures using a **Random Forest Classifier**.  
- User-friendly interface to display translated gestures as text.  

---

## **Technologies Used**  
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - OpenCV: For webcam input and image processing.  
  - Mediapipe: For hand tracking and landmark detection.  
  - NumPy & Pandas: For data handling and preprocessing.  
  - Scikit-learn: For training the Random Forest Classifier.  

---

## **Installation**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Saiphani2105/Sign-Language-Recognition-System-.git
   cd Sign-Language-Recognition-System-
   ```  
2. Install the required Python packages:  
   ```bash
   pip install -r requirements.txt
   ```  

---

## **Usage**  
1. **Run the Application:**  
   ```bash
   python inference_classifier.py
   ```  
2. Use a webcam for real-time gesture recognition.  
3. Follow the on-screen instructions to perform predefined gestures.  

---

## **Project Workflow**  
1. **Data Collection:**  
   - Hand gestures captured via webcam or dataset.  
   - Extracted hand landmarks using Mediapipe.  

2. **Preprocessing:**  
   - Normalized landmark data for consistency.  

3. **Model Training:**  
   - Random Forest Classifier trained on labeled gesture data.  

4. **Real-Time Recognition:**  
   - Webcam feed processed to detect and classify gestures.  

---

## **Results**  
- Achieved **high accuracy** in recognizing predefined gestures.  
- Successfully translated gestures into meaningful text in real time.  


---

## **Future Scope**  
- Expand the model to support dynamic sign language (gesture sequences).  
- Add support for multiple languages.  
- Deploy the system as a mobile or web application.  

---

## **License**  
This project is licensed under the [MIT License](LICENSE).  

---

## **Acknowledgments**  
- **OpenCV** and **Mediapipe** for their robust computer vision capabilities.  
- **Scikit-learn** for simplifying machine learning tasks.  
- Inspired by the need for inclusive technology solutions.  

---
