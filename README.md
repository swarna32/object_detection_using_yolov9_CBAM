# Object Detection Using YOLOv9_CBAM


## Overview
This project focuses on object detection using the YOLOv9 architecture enhanced with the Convolutional Block Attention Module (CBAM). We created and annotated our own dataset, applied YOLOv9 with CBAM, and used pretrained weights for model initialization. The trained model is capable of accurately identifying objects in images.

## Methodology

### 1. Dataset Creation and Annotation
- **Dataset**: Created and annotated for specific object detection tasks.

### 2. YOLOv9 with CBAM
- **YOLOv9**: The latest iteration of the "You Only Look Once" series, YOLOv9 provides state-of-the-art performance in real-time object detection. It is known for its speed and accuracy, making it ideal for applications requiring quick and precise object identification.
- **CBAM (Convolutional Block Attention Module)**: A lightweight and effective attention module that can be integrated into CNN architectures. CBAM sequentially infers attention maps along two separate dimensions, channel and spatial, improving the representational power of CNNs by focusing on 'what' and 'where' to emphasize.

### 3. Model Training
- **Pretrained Weights**: Utilized pretrained weights to accelerate the training process and enhance model performance.
- **Training Process**: The model was trained on the custom dataset, incorporating CBAM to refine feature learning and boost detection accuracy.

### 4. Object Detection
- The trained YOLOv9_CBAM model is deployed to identify and classify objects within images, demonstrating robust performance and precision.

## Results
- **Object Detection**: The YOLOv9_CBAM model effectively detects and identifies objects, leveraging the enhanced attention mechanism provided by CBAM for improved accuracy and reliability.
 - ![Example](https://i.ibb.co/XsxSNX5/fr.png)
 - ![Example](https://i.ibb.co/LPZwrC1/fu.png)

