# Nutrient – ML
This repository contains a transfer learning image classification model for extracting and classifying nutrient information from food labels. 

## Table of Contents
1.	Introduction
2.	Datasets
3.	Model Architecture
4.	Training
5.	Evaluation
6.	Further Work

## Introduction
NUTRIENT leverages transfer learning to extract nutrient information from images of food labels. The objective is to accurately classify and extract nutritional information from food labels to aid in dietary analysis and planning.

## Datasets
- OpenFoodFacts Dataset
  •	Utilized the OpenFoodFacts dataset for training, containing food labels and their corresponding   nutrient values.
- Custom Dataset
  •	Created a custom dataset to supplement the training data with more specific and varied examples.

## Model Architecture
Here’s a breakdown of the model architecture used:
1.	Object Detection Model:
o	The TensorFlow object detection API provides various pre-trained models that can be used for object detection tasks. These models are based on popular architectures such as Faster R-CNN, SSD (Single Shot Multibox Detector), and RFCN (Region-based Fully Convolutional Networks).
2.	Label Map Utilization:
o	The code uses label_map_util from the TensorFlow object detection API to load and handle the label map, which maps class IDs to class names.
3.	Visualization Utilities:
o	Visualization utilities from the TensorFlow object detection API are used to draw bounding boxes and labels on the images.

### Teams
- (ML) M007D4KX1441 – Bastiaans, Jessica Carmelita – Universitas Dian Nuswantoro - [Email](mailto:M007D4KX1441@bangkit.academy)
- (ML) M007D4KX1517 – Kang, Andini Wulandari – Universitas Dian Nuswantoro - [Email](mailto:M007D4KX1517@bangkit.academy)
- (ML) M283D4KX2553 – Fila Sofiyati – Universitas Negeri Semarang - [Email](mailto:M283D4KX2553@bangkit.academy)
- (CC)  C338D4KY0901 – Aji Dwi Prakoso – Politeknik Negeri Semarang - [Email](mailto:C338D4KY0901@bangkit.academy)
- (CC)  C338D4KY0933 – Ilham Rizky Harijanto – Politeknik Negeri Semarang - [Email](mailto:C338D4KY0901@bangkit.academy)
- (MD) A007D4KY3383 – The Manuel Eric Saputra – Universitas Dian Nuswantoro - [Email](mailto:A007D4KY3383@bangkit.academy)
- (MD) A338D4KY3942 – Muhammad Mizzy – Politeknik Negeri Semarang - [Email](mailto:A338D4KY3942@bangkit.academy)
![Nutrient-logo](https://github.com/Nutrient-capstone/nutrient-app/assets/91963770/8c0e91c5-b7c6-42fe-8b55-a56ad6966c9f)

