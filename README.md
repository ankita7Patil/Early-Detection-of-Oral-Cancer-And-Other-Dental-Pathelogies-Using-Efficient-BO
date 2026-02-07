# Early Detection of Oral Cancer and Other Dental Pathologies Using EfficientNet-B0

## 📌 Overview
This repository presents the implementation of a deep learning–based system for the **early detection of oral cancer and other dental pathologies** using the **EfficientNet-B0** architecture.  
The work focuses on automated multi-class classification of oral diseases from intraoral images, aiming to support dentists and healthcare professionals in early and accurate diagnosis.

This project is based on our **IEEE-published research paper**.

---

## 📄 Research Paper
**Title:** Early Detection of Oral Cancer and Other Dental Pathologies Using EfficientNet-B0  
**Publication:** IEEE  
**Authors:** Ankita Subhash Patil et al.

---

## 🦷 Disease Categories
The model classifies oral images into **six categories**:
- Oral Cancer  
- Dental Caries  
- Gingivitis  
- Hypodontia  
- Tooth Discoloration  
- Normal (Healthy Teeth)

---

## 🗂 Dataset
- Source: **Publicly available Kaggle oral disease datasets**
- Image Type: Intraoral images
- Split:
  - Training: 80%
  - Validation: 10%
  - Testing: 10%

---

## 🔧 Preprocessing Techniques
- Image resizing to **224 × 224**
- RGB conversion
- Min–Max normalization (0–1)
- Data augmentation:
  - Rotation (±15°)
  - Horizontal flip
  - Brightness & contrast adjustment

---

## 🧠 Model Architecture
- Base Model: **EfficientNet-B0 (pre-trained on ImageNet)**
- Transfer Learning applied
- Optimizer: **Adam**
- Loss Function: **Hierarchical Cross-Entropy**
- Batch Size: 32
- Epochs: 50

---

## 📊 Performance Metrics
| Model | Accuracy | Precision | Recall | F1-Score |
|------|---------|----------|--------|---------|
| DenseNet | 94% | 91% | 87% | 89% |
| ResNet | 94% | 91% | 89% | 90% |
| **EfficientNet-B0** | **95%** | **93%** | **92%** | **92%** |

✔ EfficientNet-B0 achieved the **best overall performance**.

---

## 📈 Results
- Overall Accuracy: **95%**
- F1-Score: **92%**
- Strong performance across all disease classes
- Low misclassification rate shown via confusion matrix
- No significant overfitting observed

---

## 🧪 Notebooks Included
- `EfficientNet (6).ipynb` – Main model implementation
- `ResNet.ipynb` – Baseline comparison model

---

## 🚀 Applications
- Early oral cancer detection
- Clinical decision support for dentists
- AI-assisted dental screening
- Potential use in rural and remote healthcare systems

---

## 🔮 Future Scope
- Training with larger and more diverse datasets
- Real-world clinical testing
- Mobile and web-based diagnostic applications
- Explainable AI integration (Grad-CAM)

---

## 🧑‍💻 Author
**Ankita Subhash Patil**  
CSE – Artificial Intelligence  
📧 Email: 95ankita.s.patil@gmail.com  

---

## ⭐ Acknowledgment
This project is developed as part of an academic research study and published in IEEE.

If you find this work useful, please ⭐ star the repository!
