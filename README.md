# Traffic Sign Detection using YOLOv8

This repository contains the code for training a YOLOv8 model to detect traffic signs. The data used for training the model is sourced from the [Self Driving Cars Dataset](https://universe.roboflow.com/selfdriving-car-qtywx/self-driving-cars-lfjou/dataset/6) on Roboflow Universe.

## Algorithm of Work

1. **Preparation**
   - Download and preprocess the dataset from the provided URL.
   - Install necessary libraries, including YOLOv8's requirements.
   - Configure the environment for training (e.g., GPU setup, if available).

3. **Model Configuration**
   - Define the YOLOv8 model configuration.
   - Set up data augmentation techniques to improve model robustness.

4. **Training the Model**
   - Load the preprocessed dataset.
   - Initialize the YOLOv8 model with the specified configuration.
   - Train the model on the training dataset.
   - Monitor the training process using metrics such as loss, and mAP (mean Average Precision).

5. **Evaluation**
   - Evaluate the model on the validation and test datasets.
   - Generate performance reports and visualize the results using confusion matrices, precision-recall curves, etc.

6. **Inference**
   - Use the trained model to make predictions on new, unseen data.
   - Visualize the detection results on sample images.

## Requirements

- Python 3.7+
- PyTorch
- YOLOv8 (from Ultralytics)
- OpenCV
