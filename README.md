# 🦴 Bone Fracture Detection Using Deep Learning

Welcome to our project on **automated bone fracture detection** using cutting-edge deep learning techniques. This initiative stems from a vision to improve medical diagnostics by reducing human error and speeding up X-ray image analysis — especially in critical care environments.

---

## 👩‍⚕️ Problem Statement

Bone fractures are common, yet many go undetected due to limitations in traditional diagnostic processes. Radiologists often face fatigue, overwhelming case volumes, or image quality issues — all of which may lead to delays or oversight in diagnosis.

Our mission? To build a **reliable, fast, and intelligent system** that assists in identifying fractures from X-ray images with minimal human intervention.

---

## 🚀 What We Built

We explored three deep learning models:

- 🪶 **MobileNet**  
  Lightweight and optimized for mobile/embedded devices. Ideal for real-time hospital setups with limited computational resources.
  ![image](https://github.com/user-attachments/assets/4dd4ed99-04ec-4ce4-909e-72651f538fa5)


- 🧠 **Wide ResNet**  
  A powerful convolutional network capable of handling high-dimensional medical data with precision.
  
  ![image](https://github.com/user-attachments/assets/d7104070-b1a5-42cc-8bd0-15ac54f1f06c)



- 🔬 **CustomViT (Vision Transformer)**  
  Our tailor-made architecture that merges transformer blocks with domain-specific enhancements to capture intricate patterns in bone structures.
  ![image](https://github.com/user-attachments/assets/6c089974-d4a6-4c6b-90e8-f88842602e17)


Each model was trained and evaluated on a labeled dataset of X-ray images showing fractured and non-fractured bones.

---

## 🛠️ Technical Overview

- **Data Preprocessing**: Normalization, resizing, and augmentation
- **Training Techniques**: Cross-entropy loss, early stopping, regularization
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## 📊 Performance Snapshot

| Model            | Training Accuracy | Dev Accuracy | F1 Score (Avg) |
|------------------|-------------------|--------------|----------------|
| MobileNet        | 90.06%            | 85.80%       | 0.82           |
| Wide ResNet      | 96.37%            | 93.75%       | 0.86           |
| CustomViT Model  | 98.86%            | 95.76%       | 0.85           |

> **Insight**: While CustomViT achieved the highest accuracy, Wide ResNet offered the best F1 score balance. MobileNet stands out for mobile applications.

---

## 💡 What's Next?

We plan to:
- Explore **ensemble techniques** for performance boosting  
- Deploy the models in a **web/mobile diagnostic tool**  
- Extend classification to **multi-bone and multi-fracture scenarios**

---

## 📬 Contact

For queries or collaborations, feel free to reach out:  
📧 [mandalapujashmitha2005@gmail.com](mailto:mandalapujashmitha2005@gmail.com)

---

## 🙏 Acknowledgements

Special thanks to **VIT-AP University** and the School of Computer Science for their support and mentorship throughout this research.

---

> “The future of healthcare is not just in hospitals — it's in the algorithms we train today.”  
> — Team BoneDetect AI
