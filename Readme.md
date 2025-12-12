
# Retinal OCT Pathology Classification using Deep Learning and Transfer Learning

This repository documents an approach for the crucial task of **Retinal OCT Pathology Classification**, aimed at identifying and categorizing different eye diseases from Optical Coherence Tomography (OCT) images of the retina.

Utilizing Artificial Intelligence (AI) and Machine Learning (ML) techniques, specifically deep learning and image processing, this method seeks to automate and streamline the classification process, leading to faster and more accurate diagnoses.This approach has the potential to revolutionize ophthalmology by improving diagnostic accuracy and ultimately leading to better patient outcomes.

## 🎯 Objectives

The successful implementation of this classification model aims to achieve several key objectives:

* **Automation and Speed:** To automate and streamline the classification process, reducing the burden on clinicians and enabling faster diagnoses.
* **Early Detection & Outcomes:** To improve the early detection and diagnosis of eye diseases, potentially leading to better treatment outcomes and a reduced burden on the healthcare system.
* **Personalized Treatment:** To enable the development of personalized treatment plans based on the individual patient's disease status, potentially improving treatment efficacy and reducing treatment costs.
* **Error Reduction:** To reduce the risk of human error in the interpretation of OCT images, leading to more accurate and consistent diagnoses.
* **Accessibility:** To increase the availability and accessibility of diagnostic services, particularly in underserved areas with limited access to specialized ophthalmologists.
* **Tool Development:** To contribute to the development of new diagnostic tools and techniques, expanding the range of options available to clinicians for the management of eye diseases.

## 🧠 Methods and Algorithms

The model relies on **Transfer Learning** as a core methodology, leveraging the power of pre-trained deep learning models.

### 1. Transfer Learning Feature Extraction

This is a technique used in deep learning where a pre-trained model is utilized to extract features from new data for a specific task. The pre-trained model has already learned a set of relevant features from a different but related task, allowing it to be used for feature extraction in the new task.

### 2. Transfer Learning Fine-Tuning

This technique adapts a pre-trained model to a new task by adjusting its weights through continued training on the new, task-specific data. The pre-trained model's architecture and weights are used as a starting point, and then the model is fine-tuned. This approach can lead to faster training and better performance compared to training a new model from scratch.



## ⚙️ Model Architecture and Flow

The process involves a sequence of steps from data handling to model testing, as illustrated in the diagram:



1.  **Dataset:** The OCT image dataset is used as input.
2.  **Graph Processing:** Raw data is fed into a Graph Processing step.
3.  **Pre-trained Model (VGG/ResNet/AlexNet parameters):** Pre-processed features and labels are extracted using the pre-trained model.
4.  **2-Layer CNN Algorithm:** Training and testing are performed using a 2-layer CNN algorithm.
5.  **Model Realization:** The model is realized and evaluated, followed by final testing.

## 📝 Conclusion

To summarize, the retinal OCT pathology classification model using deep learning and transfer learning techniques shows promise in accurately identifying and classifying retinal diseases. This can help with clinical decision-making and improving patient outcomes. Overall, this model is a significant step forward in the diagnosis and treatment of retinal diseases using AI and ML. However, more research is needed to ensure the model is reliable and effective in different clinical settings and populations.

---

### Contact Information

* **Name:** Narishetti Ranjith Kumar
* **Email:** ranjithchowdary2001@gmail.com

**Project Guide:** Prof M. Nivedita, VIT, SCOPE
**Institution:** Vellore Institute of Technology (VIT)
