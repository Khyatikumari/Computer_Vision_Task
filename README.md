# Computer_Vision_Task
## 🎉 aquarium-data-cots-p998v/2 🎉
## YOLOv8 Object Detection on Aquarium Dataset🤖
This project trains a YOLOv8 model on the Aquarium Dataset for object detection. The dataset contains images of various sea creatures in an aquarium environment. Using YOLOv8, we aim to detect and classify objects with high accuracy.
## Project Structure🤖
* train.py: Python script for training the YOLOv8 model on the Aquarium dataset.

* README.md: Overview and usage instructions.

* requirements.txt: Lists required libraries for easy setup.
## Requirements🤖
To run this project, you'll need:

* Google colab 

* Roboflow (for dataset management and preprocessing)

* Ultralytics YOLO (for YOLOv8)
## Installation🤖
# Step 1: Install necessary libraries
* !pip install roboflow

* !pip install wandb

* !pip install ultralytics
## Dataset Download🤖
The dataset is managed using Roboflow. To download, use the following steps:

* Sign up on Roboflow and obtain your API key.

* Replace "YOUR_API_KEY" in train.py with your actual API key.
## Training the Model🤖
This script will:

* Download the dataset using Roboflow.

* Set up and configure a YOLOv8 model.

* Train the model on the dataset for 50 epochs.

* Output metrics for analysis.
## Model Parameters and Hyperparameters🤖
In the training script (train.py), the following key parameters are set:

* epochs: 50

* batch: 16

* imgsz: 640
## Training Graph🎊
![training graph](https://github.com/user-attachments/assets/8fa3bc01-b062-414a-b4aa-ea8e63931e1b)
## Dataset🎊
![Dataset](https://github.com/user-attachments/assets/0189f40d-4ed8-4c4f-a4af-b3b3941fff2b)

## Output Metrics🤖
The model outputs the following metrics:

* Precision: Measures true positive predictions among all positives.

* Recall: Measures true positives among all actual positives.

* mAP@0.5: Mean Average Precision at IoU threshold 0.5.

* mAP@0.5:0.95: mAP across various IoU thresholds for more detailed evaluation.
## Google_Colab_Work🎊
https://colab.research.google.com/drive/1YTn1eHV9GGgQJe2nvirXkm7B9HAjfTVG?usp=sharing
## Author🤖
Khyati kumari
