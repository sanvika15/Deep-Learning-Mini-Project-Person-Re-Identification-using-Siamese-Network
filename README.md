# 🧠 Person Re-Identification using Siamese Network (Deep Learning Mini Project)

## 👩‍💻 By: Sanvika Dakhale   
**Branch:** Data Science  
**Course:** Deep Learning

---

## 📌 Project Title

**Person Re-Identification using Deep Learning – A Siamese Network Approach**

---

## 🔍 Problem Statement

Person re-identification is the task of matching people across images captured from different cameras in different environments. It is crucial for applications in video surveillance, human tracking, and smart security systems.

The challenge lies in recognizing the same individual across images that may vary in lighting, pose, resolution, and background.

---

## 💡 Project Explanation

This project presents a **Siamese Neural Network** approach for person re-identification using the **Market-1501 dataset**. The model leverages **EfficientNet-B0** as a feature extractor to generate embeddings for anchor, positive, and negative image triplets.

The network is trained using **Triplet Margin Loss**, which ensures that:
- The distance between the anchor and positive embeddings (same person) is minimized.
- The distance between the anchor and negative embeddings (different person) is maximized.

### 🔧 Key Components:
- **Model Architecture**: Siamese Network with shared EfficientNet-B0 backbone.
- **Loss Function**: Triplet Margin Loss.
- **Dataset**: Market-1501 (via Kaggle).
- **Evaluation**: Embedding similarity using Euclidean distance.

---

## 📂 Dataset Used

- **Dataset Name**: [Market-1501 Dataset](https://www.kaggle.com/datasets/pengcw1/market-1501)
- **Description**: Over 32,000 images of 1,501 identities captured from 6 different camera angles.

---

## 🛠️ Techniques Applied

| Technique | Purpose |
|----------|---------|
| Siamese Network | To learn similarity between image pairs |
| EfficientNet-B0 | Pretrained backbone for feature extraction |
| Triplet Loss | Embedding optimization for contrastive learning |
| Embedding Retrieval | Identify closest identity using distance metric |

---

## 📊 Evaluation

- Training and Validation Loss monitoring
- Qualitative image matching (retrieving closest images)
- Accuracy based on visual similarity
- Euclidean distance used for embedding comparison
