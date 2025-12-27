# Cat vs Dog Classifier CNN

A Convolutional Neural Network (CNN) project to classify images of cats and dogs using **Keras** and **TensorFlow**.

---

## Project Overview
This project uses deep learning (CNN) to distinguish between cats and dogs in images. It is built with Python, Keras, and TensorFlow.

- **Input:** Images of cats and dogs  
- **Output:** Predicted label: `Cat` or `Dog`  

---

## Dataset
The dataset used for this project is from [Kaggle: Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/data).  
> Note: Large datasets are not uploaded to GitHub. Download from the link above and place images in the correct folder structure.

Folder structure example:
data/
├─ train/
│ ├─ cats/
│ └─ dogs/
└─ test/
├─ cats/
└─ dogs/

---

## How to Run

1. **Clone the repository**  
```bash
git clone https://github.com/MudassarGill/Cat-vs-Dog-classifier_CNN.git
cd Cat-vs-Dog-classifier_CNN
jupyter notebook Cat_dog.ipynb
 If using Python script:

python Cat_dog.py
