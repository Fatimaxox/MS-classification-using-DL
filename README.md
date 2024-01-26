# Multiple Sclerosis (MS) Classification using DL 🧠🔍

Multiple Sclerosis (MS) is a persistent inflammatory disorder that affects the central nervous system, impacting approximately 2.5 million individuals worldwide. The gender ratio tilts in favor of women at around 2.01. The characteristic feature of MS includes the infiltration of immune cells into the central nervous system (CNS), causing localized inflammation, neuronal loss, and demyelination. The chronic demyelination process intensifies axonal damage, ultimately leading to atrophy—a substantial contributor to enduring neurological impairment.

## Goals and Objectives 🎯

Our primary aim is to establish a resilient and effective classification system that can discern between images associated with Multiple Sclerosis (MS) and those without. This endeavor significantly contributes to advancing the field of medical imaging analysis, particularly in the diagnosis and characterization of **Multiple Sclerosis**.

## Techniques Used 🛠️

- **Image Preprocessing:**
  - Increased **contrast** of the images.
  - Adjusted overall brightness.
  - Normalized image values between 0 and 1.

- **Deep Learning:**
  - Utilized **CNN (Convolutional Neural Network)**.
  - Consisted of four stages: (1) Data Preprocessing, (2) Building the CNN, (3) Training, and (4) Evaluation.


## Dataset 📊

The MS dataset was obtained from Kaggle consists of 3427 samples distributed across four files that showcase various imaging modalities and orientations. 
Specifically, we took the following actions:
- Merged the "Control-Axial" and "Control-Sagittal" files into a one containing 2016 samples.
- Combined the "MS-Axial" and "MS-Sagittal" files into a unified "MS" file, resulting in a total of 830 images.
- To address dataset imbalance, we adjusted the number of images in the "Control (healthy)" file, reducing it to 1213.

## Final Result 🏆

Our model achieved an excellent accuracy of 98% in identifying MS cases.

## Important Note 📌

This is a binary classification of Multiple Sclerosis cases without the use of segmentation.
