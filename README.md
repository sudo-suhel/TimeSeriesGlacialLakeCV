# Time-Series Change Detection of Glacial Lake Area Changes Using Computer Vision Techniques

This project develops an automated computer vision-based approach for monitoring glacial lake changes over time, addressing risks associated with glacial lake outburst floods (GLOFs) caused by climate change. Using satellite imagery from sources like Landsat and Sentinel-2, the methodology combines advanced segmentation algorithms and time-series analysis for accurate and efficient glacial lake mapping.

Key Features:
- Pixel-based Change Detection: Quantifies variations in lake areas to analyze climate impact patterns.
- Segmentation Algorithms: Implements ResNet and U-Net architectures for precise glacial lake segmentation.
- Evaluation Framework: Assesses model performance with metrics such as IoU and precision-recall.
- Deliverables: Open-source tools, segmented lake datasets, and research publications.
- This project supports environmental monitoring and disaster risk management by providing accessible tools for assessing glacial lake dynamics and informing climate adaptation strategies.

---

# Folder Structure

##  Directory data:

A directory containing subfolders for organizing datasets:

   - images/: Contains input images for analysis or training.
   - masks/: Stores segmentation masks corresponding to the images, used in supervised learning tasks.
   - test/: Contains test datasets for model evaluation.

Source: Kaggle [link](https://www.kaggle.com/datasets/aatishshresthaa/glacial-lake-dataset)

---

## eda.ipynb

A Jupyter notebook for exploratory data analysis (EDA), used to visualize, analyze, and understand the dataset.

---

## res_net.ipynb:

A Jupyter notebook implementing a ResNet-based model for tasks such as classification or segmentation.

---

## u_net.ipynb:

A Jupyter notebook implementing a U-Net architecture for image segmentation tasks, like detecting and delineating glacial lakes.

---

## Collaborators:
1. Sachin Malego (s.malego@gmail.com)
2. Suhel Acharya (suhel.acharya10@gmail.com)