# **Brain Tumor Detection Using Vision Transformer**  

## **Introduction**  

This project focuses on **brain tumor detection from medical images** using the **Vision Transformer (ViT)**. The model used is **ViT-B/16** from **Google**, pretrained on the **ImageNet-21k** dataset and **fine-tuned** for this specific task.  

## **Features**  

✅ **Use of Vision Transformer (ViT-B/16)** for extracting image features and accurately classifying MRI images.  
✅ **Data processing and preprocessing are automatically and efficiently handled by Hugging Face models.**  
✅ **High accuracy in detecting various brain tumors and correctly classifying MRI images.**  

## **Model**  

🧠 The **Vision Transformer (ViT-B/16)** model is used for **brain tumor detection and classification from MRI scans**.  
🔍 **Data processing and preprocessing are automatically and efficiently handled by Hugging Face models.**  

## **Dataset**  

This project uses a **combined dataset** from three different sources:  

- **figshare**  
- **SARTAJ dataset**  
- **Br35H**  

The dataset consists of **7023 human brain MRI images**, classified into **four categories**:  
1. **Glioma**  
2. **Meningioma**  
3. **No Tumor** (images from the **Br35H** dataset)  
4. **Pituitary**  

⚠ **Note:** In the **SARTAJ dataset**, the images of the **Glioma** class were not correctly categorized. This issue was identified through reviewing the results of different models and comparing them with other works. As a result, the images from this folder were removed and replaced with images from the **figshare** collection.  

📂 Dataset link on **Kaggle**:  
[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)  

## **Model Performance**  

The model was evaluated on the test data, and the following results were obtained:  

🔹 **Accuracy:** 99%  
🔹 **Precision:** 99%  
🔹 **Recall:** 99%  
🔹 **F1-Score:** 99%  

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| Glioma (0) | 98% | 99% | 98% | 281 |
| Meningioma (1) | 99% | 97% | 98% | 243 |
| No Tumor (2) | 100% | 99% | 100% | 334 |
| Pituitary (3) | 98% | 99% | 98% | 285 |
| **Overall Average** | **99%** | **99%** | **99%** | **1143** |

## **Contributions**  

💡 You can contribute by **improving the model, optimizing performance, reporting issues**, or **adding new features** to enhance this project!
