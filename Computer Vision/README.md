
### **Project Overview**

**Objective**:
- The goal of this research is to enhance breast cancer detection rates using deep learning techniques, specifically Convolutional Neural Networks (CNNs) and Vision Transformers (ViT). The study focuses on classifying various types of breast cancer, including invasive ductal carcinoma (IDC) and ductal carcinoma in situ (DCIS), leveraging both the CBIS-DDSM and IDC histopathology datasets.

**Datasets Used**:
- **IDC Dataset**: Contains 162 whole-mount slide images scanned at 40x, with 277,524 50x50 patches, including both IDC-negative and IDC-positive images.
- **CBIS-DDSM Dataset**: A standardized collection of mammogram images, with 6,775 studies and 10,239 images, spanning normal, benign, and malignant conditions.

### **Methodology**

- **Preprocessing**: 
  - Image resizing, normalization, and data augmentation (rotations, flips, etc.) were applied to enhance model generalization and improve performance.
  
- **Proposed Framework**:
  - A hybrid model combining CNNs with Vision Transformers (ViT) for better performance in classifying medical images as benign or malignant.
  
- **Model Architectures**:
  - **CNN**: Traditional CNN model using layers for feature extraction and classification.
  - **Xception**: Uses depthwise separable convolutions for more efficient image classification.
  - **EfficientNetB0**: Scales network size to achieve state-of-the-art performance with minimal computational cost.
  - **Prov-GigaPath**: A deep learning model optimized for large-scale data processing, ideal for high-throughput applications.
  - **ViT**: Leverages transformer architecture for image classification by dividing images into patches and using self-attention mechanisms.

### **Model Development**:
- Several models were tested, including CNN and various hybrid architectures (Xception+ViT, EfficientNetB0+ViT, Prov-GigaPath).
  
- **Evaluation Metrics**:
  - Performance was measured using accuracy, precision, recall, F1-score, and confusion matrix.

### **Results**

- **CBIS-DDSM Dataset**:
  - Best performance was achieved by the **Xception+ViT** model with:
    - Accuracy: 96.8%
    - Precision: 96%
    - Recall: 97%
    - F1-score: 96%
  
- **IDC Dataset**:
  - **Prov-GigaPath** outperformed other models with:
    - Accuracy: 93.23%
    - Precision: 90.42%
    - Recall: 85.15%
    - F1-score: 80%

- Data augmentation techniques improved recall significantly, especially for the hybrid models like **Xception+ViT**.

### **Discussion**
- The **Xception+ViT** model performed well on the CBIS-DDSM dataset, providing high recall and minimal false negatives, which is crucial in cancer detection. 
- **Prov-GigaPath** was superior on the IDC dataset, delivering high accuracy.
- Augmentation improved model generalizability, but challenges in computational costs and optimal hyperparameter tuning remained.

### **Conclusion**
- The **Xception+ViT** hybrid model achieved the best recall on the CBIS-DDSM dataset, highlighting the potential of combining CNNs with ViT for improving breast cancer detection.
- **Prov-GigaPath** was the best performer for the IDC dataset.
- Future work should focus on improving computational efficiency, integrating datasets for broader generalization, and fine-tuning augmentation strategies for better performance.

