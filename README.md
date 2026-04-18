# Surface Defect Detection using Deep Learning

##  Overview
This project focuses on automated **surface defect classification and detection** using deep learning techniques. The system identifies four defect types:

- Crack  
- Gap  
- Pit  
- Scratch  

We perform a **comparative and ablation study** using CNN-based models and object detection models.

---

##  Key Features
- Comparison of **CNN models (ResNet50, DenseNet121)** and **Detection models (YOLOv8, SSD)**
- Ablation study on:
  - Multi-scale feature extraction
  - Attention mechanisms (SE vs CBAM)
  - Input resolution (224 vs 320)
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
  - ROC Curve

---

##  Results Summary
- **Best Model:** YOLOv8 (320×320)
- **F1-score:** 0.8469
- Detection models outperform classification models
- **SE attention > CBAM**
- Higher resolution improves detection performance

---

##  Dataset
- Total Images: 567  
- Classes: Crack, Gap, Pit, Scratch  
- Split:
  - Train: 70%
  - Validation: 15%
  - Test: 15%

---

##  Models Used

### Classification Models
- ResNet50
- DenseNet121
- Multi-scale CNN
- SE Attention
- CBAM Attention

### Detection Models
- YOLOv8
- SSD

---

##  Installation

```bash
git clone https://github.com/Coder-Anushka-Jain/surface-defect-detection.git
cd surface-defect-detection
pip install -r requirements.txt
