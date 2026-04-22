---
title: SmartVision AI
emoji: 🔍
colorFrom: blue
colorTo: indigo
sdk: streamlit
sdk_version: 1.36.0
app_file: Step10_streamlit_app.py
pinned: false
python_version: 3.10
---

# SmartVision AI — Multi-Class Object Recognition

Streamlit app that combines an image-classification model (transfer learning: MobileNetV2 / EfficientNetB0 / ResNet50 / VGG16) with a YOLOv8 object detector, trained on a 25-class subset of COCO.

## Pages
- **Home** – project overview
- **Classification** – upload an image, get the predicted class
- **Detection** – upload an image, see bounding boxes
- **Model Performance** – accuracy, inference time, model size comparisons
- **About** – dataset and model details
