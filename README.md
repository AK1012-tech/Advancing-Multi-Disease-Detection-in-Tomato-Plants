# Advancing-Multi-Disease-Detection-in-Tomato-Plants
Reframed traditional disease classification into an object detection task using YOLO models, achieving up to 96.3% mAP with YOLOv9 on a custom 9-class PlantVillage dataset.

# Abstract
This study tackles the challenge of detecting multiple tomato leaf diseases by shifting from traditional classification to object detection. Initially using models like VGG16 and ResNet101, the focus later moved to the YOLO framework for precise detection. A hybrid background removal method was introduced, and explainable AI (LRP heatmaps) enhanced interpretability. YOLOv9 achieved the highest mAP of 96.3%, outperforming earlier versions and highlighting improved accuracy and transparency.

# Proposed Architecture
1. Image Classification
  ![image](https://github.com/user-attachments/assets/3c3c57a7-dff3-4e2a-a1f3-7efe19a3da87)

2. Object Detection
  ![image](https://github.com/user-attachments/assets/900dd384-93ae-4771-9488-5aa28ccf9660)

# Algorithm
1. converting the image to grayscale 
2. learning background distribution with a GMM model, 
3. creating a binary foreground mask,
4. refining the mask with morphological closing,
5. using GrabCut for further refinement based on the mask, and
6. removing the background using the final mask.

# Model Performance
1. Classification models
   ![image](https://github.com/user-attachments/assets/989627be-3a05-481f-a659-e6f8a29d0049)

2. Object detection models
   ![image](https://github.com/user-attachments/assets/950aaf56-fc81-4a3e-a5a4-5a258816281d)

# Results
1. Predictions of Classification model (Ensemble Model)
   ![image](https://github.com/user-attachments/assets/63172da2-6422-4c74-9446-180430931d0d)

2. Predictions of Object Detection Model (YOLOv9)
   ![image](https://github.com/user-attachments/assets/6f484895-a9f1-4d59-8e88-5aa713aadf95)




   
