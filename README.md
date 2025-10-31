# Lung-Cancer-Prediction-Using-Vision-Transformers

The Lung Cancer Detection project aims to address the global challenge of lung cancer-related deaths by enabling early and accurate diagnosis through advanced deep learning techniques. This hybrid framework integrates the strengths of Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to enhance the accuracy and reliability of lung cancer classification.

CNNs are employed for local feature extraction, identifying crucial regions and textures in CT and X-ray images. Meanwhile, ViTs capture global context and fine-grained details using self-attention mechanisms, allowing the model to better differentiate between benign, malignant, and normal lung cases. Together, this hybrid approach provides improved diagnostic precision and interpretability.

The proposed model includes a robust preprocessing pipeline, feature extraction, and a classification module that collectively enhance sensitivity and specificity. It supports radiologists by reducing diagnostic errors, improving consistency, and facilitating early intervention for patients.

-> Model Performance (Vision Transformer Results)
Class	Precision	Recall	F1-Score
Benign cases	91%	82%	86%
Malignant cases	100%	76%	86%
Normal cases	85%	98%	91%

The results show that the Vision Transformer model achieves high accuracy and robustness across all three classes, with especially strong performance in detecting normal cases (F1-score: 91%) and high precision in malignant case identification (100%). These outcomes demonstrate the capability of ViTs to capture complex patterns and improve classification reliability.

-> Highlights

Early and accurate detection of lung cancer.

Hybrid CNN-ViT model for both local and global feature analysis.

Enhanced sensitivity and specificity in classification.

Explainable, AI-driven support for radiologists.

Contributes to improved patient outcomes and reduced diagnostic delays.
