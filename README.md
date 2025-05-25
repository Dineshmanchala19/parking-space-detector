# Parking Space Detection using YOLOv8

## Project Overview
This project leverages the state-of-the-art YOLOv8 object detection model to accurately identify parking spaces in images. Using a custom dataset of 1232 annotated images, the model is trained and validated to provide reliable parking space detection, useful for smart parking systems and traffic management.

## Dataset Details
- **Total Images:** 1232
- **Data Split:**
  - **Training:** 70% (approx. 862 images)
  - **Validation:** 20% (approx. 246 images)
  - **Testing:** 10% (approx. 124 images)

The dataset includes diverse parking scenarios to ensure robust model performance across different environments.

## Model Architecture
- **YOLOv8**: The latest iteration of the You Only Look Once (YOLO) series, renowned for its balance of accuracy and speed in real-time object detection.
- The model is trained to detect and localize parking spaces in images, enabling effective parking slot detection and monitoring.

## Usage Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/parking-space-detector.git
cd parking-space-detector
2. Set Up the Environment
Ensure you have Python installed along with the required libraries. You can install dependencies 

3. Training and Validation
Open and run the Jupyter Notebook cark-parkingspace-detection.ipynb to train the YOLOv8 model on your dataset.

The notebook contains steps for loading data, model configuration, training, and evaluation.

4. Testing and Inference
Use the trained model to perform inference on new images.

Evaluate the model's performance on the test set to check detection accuracy.

Project Structure
├── cark-parkingspace-detection.ipynb   # Main notebook with training & evaluation
├── dataset/                            # Folder containing images and annotations
│   ├── train/
│   ├── val/
│   └── test/                   # Python dependencies
└── README.md                          # Project documentation
Notes
The dataset is split randomly to ensure a balanced representation for training, validation, and testing.

This project is intended for academic and experimental purposes; adjust and optimize hyperparameters as needed for production use.

Ensure your hardware supports training YOLOv8 models efficiently (preferably with a CUDA-enabled GPU).
