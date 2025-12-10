# 🐶🐱 Dogs vs Cats – Image Classification in Keras

-This project trains a Convolutional Neural Network (CNN) to classify images of **dogs** and **cats** 


-[Kaggle Dogs vs Cats dataset](https://www.kaggle.com/datasets/biaiscience/dogs-vs-cats).  

-It demonstrates a complete deep-learning workflow including data preparation, augmentation, model training, evaluation, and prediction.

| Attribute             | Description                                               |
| --------------------- | --------------------------------------------------------- |
| **Dataset Name**      | **Dogs vs Cats Image Classification**                            |
| **Total Images**      | **37,500** (approx.)                                      |
| **Training Images**   | **20000**                                                |
| **Validation Images**    | **5000**                                                 |
| **Validation Images** | **12500**                                                  |
| **Number of Classes** | **2** (Dod ,Cat) |
| **Data Format**       | **JPEG Images**                                           |

---

---
## 📌 1. Project Objectives

- Build a **binary image classifier** (`dog` vs `cat`)
- Use **data augmentation** to improve generalization
- Monitor **training vs validation performance** and detect overfitting
- Visualize predictions on sample images
- Provide a clean, reusable notebook for Colab or Kaggle

---

## 📂 2. Dataset

- **Dataset source:** Kaggle  
  **`biaiscience/dogs-vs-cats`**
- **Classes:** `cat`, `dog`
- RGB JPG images with varying resolutions

This notebook creates a `DataFrame` containing:
- `filename` — e.g. `dog.1234.jpg`
- `category` — `"dog"` or `"cat"`

Dataset is split into:
- **80% training**
- **20% validation**

---

## ⚙️ 3. Environment & Requirements

The notebook runs on **Google Colab** (GPU recommended) or **Kaggle Notebooks**.

### Main libraries:
- `python 3`
- `tensorflow` / `keras`
- `numpy`
- `pandas`
- `matplotlib`
- `opencv-python`
- `scikit-learn`
---
## 📂 Project Structure
```bash
├── Image_Classification_Colab.ipynb   # main notebook
├── README.md                          # this file
├── data/
│   ├── train/train                         # training images (cats & dogs)
│   └── test/test                         # test / inference images (optional)
           
---
