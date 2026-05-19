# SmartVision AI

## Intelligent Multi-Class Object Recognition System

SmartVision AI is a deep learning based image classification project that recognizes objects from selected COCO dataset categories. The project uses transfer learning with four pre-trained CNN models and provides a Streamlit web application for real-time image prediction.

## Project Objective

The main objective of this project is to build an intelligent object recognition system using COCO dataset images. The system trains and compares multiple deep learning models and allows users to upload an image through a web app to predict the object category.

## Dataset

The dataset is prepared from the COCO dataset.

- Dataset source: COCO / Hugging Face COCO dataset
- Number of categories: 25
- Images per class: 100
- Total images: approximately 2500
- Image size: 224 x 224 pixels
- Split ratio:
  - Training: 70%
  - Validation: 15%
  - Testing: 15%

## Selected Classes

The project uses selected object categories such as:

- person
- bicycle
- car
- motorcycle
- airplane
- bus
- truck
- traffic light
- stop sign
- bench
- bird
- cat
- dog
- horse
- cow
- elephant
- bottle
- cup
- bowl
- pizza
- cake
- chair
- couch
- potted plant
- bed

## Models Used

Four transfer learning models are trained and compared:

1. VGG16
2. ResNet50
3. MobileNetV2
4. EfficientNetB0

All models use ImageNet pre-trained weights and are fine-tuned for multi-class object classification.

## Project Workflow

1. Import required libraries
2. Load COCO dataset
3. Select 25 object categories
4. Collect 100 images per class
5. Create train, validation, and test folders
6. Preprocess and resize images
7. Train four transfer learning models
8. Evaluate model performance
9. Compare model accuracy
10. Save trained models
11. Build Streamlit web application
12. Test image prediction using the app

## Folder Structure

```text
SmartVisionAI/
├── models/
│   ├── VGG16_smartvision.keras
│   ├── ResNet50_smartvision.keras
│   ├── MobileNetV2_smartvision.keras
│   ├── EfficientNetB0_smartvision.keras
│   ├── class_names.txt
│   └── model_comparison_results.csv
├── app.py
├── requirements.txt
└── README.md