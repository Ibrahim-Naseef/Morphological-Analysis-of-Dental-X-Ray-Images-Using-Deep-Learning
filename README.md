# 🦷🧠 Morphological Analysis of Dental X-Ray Images Using Deep Learning 🧠🦷

## 🚨 Important Notice 🚨

This project is currently under **patent process**. As a result, the code, dataset, and model files cannot be shared publicly at this time. We appreciate your understanding and interest in our work.

## 📋 Table of Contents
- [📖 Introduction](#introduction)
- [🎯 Objectives](#objectives)
- [🛠️ Methodology](#methodology)
- [✨ Features](#features)
- [📊 Results and Discussions](#results-and-discussions)
- [🔮 Future Work](#future-work)
- [👥 Contributors](#contributors)


## 📖 Introduction

Manual analysis of dental X-ray images is often time-consuming, prone to human error, and subject to inter-observer variability. This project aims to automate this process, providing dentists and researchers with a reliable and efficient tool for large-scale analysis of dental morphology.

## 🎯 Objectives

1. **Automate the identification of individual teeth** within dental X-ray images, focusing on the lower jaw region.
2. **Accurately determine positions and labels** of each identified tooth.
3. **Extract precise morphological measurements** such as length, width, angle, and apex condition.
4. **Classify and quantify tooth morphology** to aid in dental research and clinical diagnosis.
5. **Streamline diagnostic workflows** and enhance the efficiency of dental care services through automated analysis.

## 🛠️ Methodology

The project employs two YOLOv8 models:
- **Tooth Detection Model:** Detects the tooth area within dental X-ray images.
- **Instance Segmentation Model:** Identifies individual lower jaw teeth within the detected tooth area.

### System Architecture
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/fb9ec840-1409-485c-9f6d-ed738c9ba91e)
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/ac824404-55d1-4cbc-b8fc-8a75fc256b01)

### Steps Involved:
1. **Preprocessing:** Optimize dental X-ray images by resizing, grayscale conversion, and normalization.
2. **Annotation:** Label individual teeth using Roboflow software and apply augmentations.
3. **Dataset Splitting:** Divide the dataset for training, validation, and testing (70-20-10 split).
4. **Model Training:** Use YOLOv8 architectures for accurate tooth detection and segmentation.
5. **Prediction:** Apply trained models to identify each tooth in new X-ray images.
6. **Post-processing:** Extract morphological features like length, width, angle.

### Technology Stack:
- **Deep Learning:** YOLOv8
- **Web Framework:** Python Django, HTML, CSS
- **Database:** MySQL

## ✨ Features

- **Automated Dental X-ray Analysis**
- **Accurate Tooth Detection and Segmentation**
- **Precise Morphological Measurements**
- **Web-Based Application for User Interaction**

## 📊 Results and Discussions

The automated analysis system significantly enhances diagnostic accuracy and efficiency in dental care by reducing human error and time consumption. Detailed results and discussions can be found in the project documentation.

### Annotation process using Roboflow
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/babd25fc-86ac-4d82-adf6-8f69a9b1c3cd)

### Home Page
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/e697bdfb-cf12-4dd8-8b50-98ba6c1ccc21)

### Signup
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/818f7ce6-f8c9-4466-b928-febb63c1c73b)

### Login 
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/8e2f7716-8e6a-4d2a-a2de-19700c8d025c)

### Contact
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/3c27ab02-38dc-45f1-a197-a1fa1380f7e0)

### Analysis 
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/848deef3-61e1-4387-8768-53518035d9a7)

### Bounding box detection
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/f4477f3b-bbf9-4fac-a56f-8f9e41cbb682)

### Intsance segmentation detection
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/31c626cb-6419-41d9-b337-2c7b3ade4f25)

### Individual tooths and Morphological Features
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/a7650e80-965c-401b-a8e0-7a850c73fb6d)

### Individual tooths(Masks) and Morphological Features
![image](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/0e1fe6ef-438d-4594-878a-6fe1b57e7096)

### Demo
![Dent-Techand14morepages-Personal-MicrosoftEdge2024-05-1523-16-32-ezgif com-crop](https://github.com/Ibrahim-Naseef/Morphological-Analysis-of-Dental-X-Ray-Images-Using-Deep-Learning/assets/156147657/4d5f4cfc-c1c7-478a-b959-a2a8d66de78d)

## 🔮 Future Work

Future advancements may include:
- Integrating 3D imaging technology for deeper insights into dental structures.
- Expanding disease analysis to include root canal infections and periodontal diseases.
- Incorporating decision support systems for real-time insights and personalized treatment recommendations.

## 👥 Contributors

- **Ibrahim Naseef** (4DM20CS019)
- **Mohamed Sahil** (4DM20CS027)
- **Samarth Premanand Naik** (4DM20CS043)
- **Souparnika S D** (4DM20CS052)

