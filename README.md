# Machine Learning and Deep Learning Approaches for Diagnosis of Glaucoma using Retinal Fundus Images

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features and Techniques](#features-and-techniques)
- [Usage](#usage)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Future Work](#future-work)

## Introduction
This project aims to develop a machine learning model for the detection of glaucoma using image classification techniques. By analyzing images of the retina, the model seeks to identify characteristics indicative of glaucoma, facilitating early diagnosis and intervention to prevent vision loss.

## Dataset
The project utilizes several publicly available datasets, including:
- **ORIGA**: Contains training and testing images labeled for glaucoma and normal cases.
- **DRISHTI-GS**: Provides high-quality images for retinal analysis.
- **G1020**: Offers a collection of glaucoma and normal images for comprehensive evaluation.

Images are organized into two main categories: **Glaucoma** and **Normal**.

## Features and Techniques

### Data Preparation:
- Images are sorted into separate folders based on their labels.

### Feature Extraction:
- **Gray Level Co-occurrence Matrix (GLCM)**: Analyzes spatial relationships of pixels to capture texture features.
- **Histogram of Oriented Gradients (HOG)**: Extracts edge and shape information from images.

### Model Training:
- A **Linear Regression** model is trained on the extracted features to classify the images.

## Evaluation Metrics
The model's performance is evaluated using the following metrics:
- **Accuracy**: Proportion of correctly classified instances.
- **Precision**: Measure of the accuracy of positive predictions.
- **Recall**: Ability of the model to find all relevant cases.
- **F1 Score**: Harmonic mean of precision and recall, providing a balance between the two.
- **Mean Squared Error (MSE)**: Measures the average of the squares of the errors, indicating the quality of predictions.

## Results
The project results indicate that the **Gray Level Co-occurrence Matrix (GLCM)** feature extraction method yielded higher accuracy compared to the **Histogram of Oriented Gradients (HOG)** method. The project successfully developed a glaucoma detection model that achieved approximately **85% accuracy**. Additionally, the use of machine learning models beyond linear regression can potentially improve classification accuracy, indicating room for enhancement in future iterations.

## Future Work
- Explore advanced deep learning architectures (e.g., **CNNs**) for improved accuracy.
- Implement **transfer learning** models to further improve accuracy.

