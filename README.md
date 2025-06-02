# Automated Plant Disease Detection


# 🍃 Binary Classification of Apple Leaf Diseases with CNN

This project demonstrates a deep learning pipeline for binary classification of apple leaves as either **Healthy** or **Diseased** using Convolutional Neural Networks (CNNs). It is built using PyTorch and fine-tunes a pretrained ResNet18 model on a subset of the PlantVillage dataset.

> 🔬 **Goal**: Automate plant disease detection and showcase the viability of binary classification for real-world agricultural applications.

---

## 📂 Dataset

We use a modified version of the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease), filtered to include:
- Healthy apple leaves
- Diseased apple leaves (merged from _Powdery_ and _Rust_)



--- 
## 🍃 Binary Classification of Apple Leaf Diseases with CNN
main

This project demonstrates a deep learning pipeline for binary classification of apple leaves as either **Healthy** or **Diseased** using Convolutional Neural Networks (CNNs). It is built using PyTorch and fine-tunes a pretrained ResNet18 model on a subset of the PlantVillage dataset.

🔬 **Goal**: Automate plant disease detection and showcase the viability of binary classification for real-world agricultural applications.

## 🧠 Model Architecture

- Backbone: `ResNet18` pretrained on ImageNet
- Final layer modified for binary classification
- Loss function: `BCEWithLogitsLoss`
- Optimizer: `Adam`
- Framework: `PyTorch`

---

## 📈 Results

- ✅ **Test Accuracy**: 96%
- ✅ **Recall for Healthy Class**: 100%
- 📉 Validation loss plateaued early, indicating slight overfitting

Interactive Demo (legacy multiclass version): [🌐 View Demo](https://plantdiseasencml.vercel.app/)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/leaf-disease-binary-classification.git
   cd leaf-disease-binary-classification

## 🛠️ Installation
> Assumes Python ≥ 3.8 and a CUDA-capable GPU (optional but recommended).

```bash
# Clone the repo
git clone https://github.com/yourusername/plant-disease-detection.git
cd plant-disease-detection

# Create & activate a virtual environment
python3 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate.bat     # Windows

# Install dependencies
pip install -r requirements.txt
```
