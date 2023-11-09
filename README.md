# Automated Glioma Tumor Segmentation and Classification

## Overview

This repository hosts a research project aimed at revolutionizing the diagnosis and treatment planning of aggressive brain glioma tumors in adults. Leveraging cutting-edge Magnetic Resonance Imaging (MRI) and Artificial Intelligence (AI), our goal is to provide an automated system that overcomes the challenges associated with current manual methods, including subjectivity, high costs, time consumption, and the need for specialized expertise.

## Features

- **Automated Segmentation:** Utilizing deep learning algorithms, our system accurately segments various parts of adult diffuse gliomas, enhancing efficiency and reducing subjectivity.
  
- **Multimodal Imaging:** The model incorporates robust feature extraction techniques and multimodal imaging to improve classification accuracy, contributing to early diagnosis and effective treatment planning.

- **Deep Learning Architecture:** The segmentation model achieves a remarkable Dice Coefficient of 0.7772 using a 3D Unet with (3,3,3) Kernel size, 16 layers, and trained over 100 epochs.

## Getting Started

Follow these steps to get started with our project:

All Ipynbs are individual files, using the Brats 2021 data (for segmentation) or the TCGA dataset (for classification).

## Results

Our model has demonstrated significant promise in achieving accurate glioma tumor segmentation and classification. The best Dice Coefficient obtained is 0.7772, showcasing the effectiveness of the proposed deep learning architecture.
For type of tumor classification, we achieved 90% accuracy and for sub-type we achieved 84% accuracy.


## Future Work

We are committed to continuous improvement and welcome contributions from the community. Future plans include:

- Refinement of the deep learning architecture for even higher accuracy.
- Integration of additional data sources and modalities for enhanced performance.
- Collaboration with medical professionals for real-world validation and deployment.


## Acknowledgments

We would like to express our gratitude to the open-source community for their invaluable contributions to the field of medical imaging and artificial intelligence.
Our Professor and mentor for the project, Prof. Priyankya Verma
Feel free to explore, contribute, and make a difference in the field of glioma tumor detection!
