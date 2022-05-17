# 1 3D- Brain-Mri-Segmentation
BraTs (Brain Tumor Segmentation)
## 1.1 About
**This project deals with segmentation model to diagnose brain tumor using BraTS 2018 dataset.**

<par> BraTS has always focused on evaluating cutting-edge approaches for brain tumour segmentation in multimodal magnetic resonance imaging (MRI) data. BraTS 2018 focuses on the segmentation of inherently heterogeneous (in appearance, form, and histology) brain tumours, mainly **gliomas**, using multi-institutional pre-operative MRI images. Furthermore, BraTS'18 focuses on the prediction of patient overall survival using integrative analyses of radiomic characteristics and machine learning techniques to highlight the clinical value of this segmentation job.</par>

## 1.2 Model
![U-Net model](https://user-images.githubusercontent.com/85225054/168800841-08b5de35-126e-45c9-9aec-468a2f5608ce.jpg)

## 2 Dataset

## 2.1 Overview
**MRI Dataset**

File: &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;  &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;        A File has Multi-Modal MRI Data of one person

File Format: &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;  &ensp;    &ensp;              nii.gz

Image Shape:   &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;             240(Slide Width) × 240(Slide Height) × 155(Number of Slide) × 4(Multi-mode)

![channel](https://user-images.githubusercontent.com/85225054/168802800-34376085-4582-4312-a717-796adca37b4f.jpg)

   channel 0: background

   channel 1: necrotic and non-enhancing tumor

   channel 2: edema

   channel 3: enhancing tumor



                         
