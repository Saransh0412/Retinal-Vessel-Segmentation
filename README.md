# 👁️ Retinal Vessel Segmentation using Image Processing (DIP)

This repository contains a Digital Image Processing (DIP) project focused on segmenting retinal blood vessels from fundus images using traditional computer vision techniques in Python. The goal is to assist in early diagnosis of diseases like diabetic retinopathy and glaucoma.

---

## 📂 Contents

* `DIP_RetinalEDA.ipynb`: Exploratory Data Analysis (EDA) on retinal images.
* `dip-final-retinalvesselsegmentation.ipynb`: Final pipeline for vessel segmentation using morphological operations, CLAHE, and thresholding.

---

## 🧠 Key Features

* 📊 **EDA on Retinal Images**
  Basic visualization and histogram analysis for understanding pixel intensity and color channel behavior.

* ⚙️ **Preprocessing Techniques**

  * Channel extraction (especially green channel for contrast)
  * CLAHE (Contrast Limited Adaptive Histogram Equalization)
  * Morphological operations (Opening, Closing)
  * Gaussian Blurring

* 🧪 **Segmentation**

  * Thresholding (Otsu and manual)
  * Vessel enhancement
  * Binary mask generation

* 🖼️ **Visualization**

  * Side-by-side image comparisons
  * Overlay of segmented vessels on original images

---

## 🔧 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

### `requirements.txt`:

```
numpy
matplotlib
opencv-python
scikit-image
```

---

## 🏁 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/Narayan0910/retinal-vessel-segmentation.git
   cd retinal-vessel-segmentation
   ```

2. Open the notebooks:

   * `DIP_RetinalEDA.ipynb`
   * `dip-final-retinalvesselsegmentation.ipynb`

   Run the cells step-by-step to visualize and segment retinal vessels.

---

## 📸 Sample Output

Original vs Segmented Image (example):

| Original Image                   | Segmented Vessels                  |
| -------------------------------- | ---------------------------------- |
| ![original](assets/original.png) | ![segmented](assets/segmented.png) |

(Add your own image paths here in an `/assets/` folder)

---

## 📚 Dataset

You can use any public dataset of retinal fundus images. Example:

* **DRIVE**: [https://drive.grand-challenge.org/](https://drive.grand-challenge.org/)

---

## ✍️ Authors

* \[Shruti] – B.Tech CSE – Digital Image Processing Project
* \[Saransh] – B.Tech CSE – Digital Image Processing Project

---

## 📄 License

This project is open-source and available under the MIT License.



