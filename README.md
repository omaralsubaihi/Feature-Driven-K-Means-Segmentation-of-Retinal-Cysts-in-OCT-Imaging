# Retinal Cyst Segmentation in OCT Imaging

This repository contains a Python-based pipeline for the automated segmentation of retinal cysts in Optical Coherence Tomography (OCT) images. The approach utilizes a feature-driven K-Means clustering method (incorporating intensity and "blobness" features) to reliably separate dark cysts from bright retinal backgrounds.

## Key Features

* **Preprocessing:** Includes Contrast Limited Adaptive Histogram Equalization (CLAHE), bilateral filtering, and Otsu thresholding to isolate the retinal Region of Interest (ROI).
* **Segmentation:** Unsupervised feature-driven K-Means clustering inspired by Girish et al. (2020), combined with morphological operations for post-processing and noise removal.
* **Evaluation:** Calculates standard quantitative metrics including Intersection over Union (IoU), Dice Coefficient, Sensitivity, and Specificity.
* **Visualization:** Generates side-by-side qualitative comparisons and False Positive/False Negative color overlays.

---
*This project was developed as part of the CSC8628 assignment.*
