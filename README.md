# Playing Cards Object Detection Using YOLOv8

This project focuses on training a YOLOv8 object detection model to identify different playing cards from a custom dataset. The goal is to detect and classify individual cards in real-time scenarios, demonstrating the power of deep learning for object detection.

## Dataset
- **Source**: [Kaggle Playing Cards Object Detection Dataset](https://www.kaggle.com/datasets)
- Contains annotated images of playing cards with bounding boxes.

## Tools & Technologies
- Python
- OpenCV
- PyTorch
- Ultralytics YOLOv8
- Matplotlib, Seaborn
- PIL, NumPy

## Model Training
- Base model: `yolov8n.pt` (nano version for speed and lightweight deployment)
- Trained for **30 epochs** on custom dataset using annotated `.yaml` config file.
- Evaluated with metrics: Achieved high performance with precision of 95.7%, recall of 97.7%, mAP@50 of 98.3%, and mAP@50-95 of 91.4%.
  
## Results
- Achieved high accuracy on validation data.
- Visualized predictions using confidence thresholding and bounding box overlays.

## Inference
- Performed inference on unseen validation images.
- Visualized predictions using bounding boxes and class labels.
