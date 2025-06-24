# Brain Tumor Detection – VGG16, VGG19, and InceptionV3 Models
![Brain Tumor Banner](https://www.mathewsopenaccess.com/userfiles/images/Psychiatry/Figure%201(2).png)

This project builds on a well-structured notebook originally created by **Ruslan Klymentiev**, which uses CNNs and VGG-16 for classifying brain MRI scans as tumor or non-tumor.

I used the original structure for data loading and preprocessing, then built and compared **three different CNN models**: **VGG16**, **VGG19**, and **InceptionV3** — with custom modifications and evaluation techniques.

---

## Key Highlights

- Applied and compared **VGG16**, **VGG19**, and **InceptionV3** architectures
- Tuned training strategies including freezing layers and fine-tuning
- Implemented custom focal loss for class imbalance handling
- Added training visualizations and model performance comparison

---

## Dataset

- Brain MRI Images for Brain Tumor Detection  
- [Kaggle Dataset Link](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## Tech Stack

- Python
- TensorFlow / Keras
- scikit-learn
- Matplotlib & Plotly
- Jupyter Notebook

---

## Note on Model Files

> The pretrained `.h5` files (e.g., `vgg16_weights.h5`, `inception_v3_weights.h5`) are **not included** in this repository due to GitHub’s 100MB file size restriction.  
> If needed, you can:
> - Download them directly from the [Keras Applications GitHub](https://github.com/keras-team/keras-applications/releases)
> - Or let `tensorflow.keras.applications` automatically download them during runtime

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/brain-tumor-detection-custom-model.git
   cd brain-tumor-detection-custom-model
   
2. Open the notebook using Jupyter or VSCode:
   ```bash
   jupyter notebook Abdullah_brain_tumor_detection.ipynb

3. Run all cells in order.

   Make sure the dataset path is correct and that the model files are either downloaded manually or automatically through TensorFlow/Keras.

---

## Acknowledgements

- Original Notebook Author: [Ruslan Klymentiev](https://www.kaggle.com/ruslanklymentiev)
- Dataset from: [Navoneel Chakrabarty](https://www.kaggle.com/navoneel)
- Adapted and extended by: **Abdullah Dahabre**

---

## License

This project is licensed under the [MIT License](LICENSE).  
Parts of the original notebook by [Ruslan Klymentiev](https://www.kaggle.com/ruslanklymentiev) are used with proper attribution for educational purposes only.
