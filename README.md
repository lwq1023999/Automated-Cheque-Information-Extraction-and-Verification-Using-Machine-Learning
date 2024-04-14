# Automated Cheque Information Extraction and Verification Using Machine Learning

This repository contains code and notebooks for automating cheque information extraction and verification using machine learning techniques. The project focuses on detecting cheque objects, performing OCR (Optical Character Recognition), and utilizing YOLOv8 models for epoch and version comparisons.

## Requirements

To run the provided notebooks and scripts, ensure you have the following dependencies installed that are written in the [requirments.txt](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/requirements.txt). Below are some of the example.
- Python 3.6+
- OpenCV
- pandas
- matplotlib
- Tesseract-OCR
- PyTesseract
- YOLOv8 for object detection

## Instructions
1. Clone or download this repository to your local machine.
2. Install the required [dependencies](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/requirements.txt).  using pip.
3. Download the pre-trained model
4. Use the following Python code to load the custom-trained YOLOv8 model:
   ```python
   from yolov8 import YOLO

   # Load the custom trained model
   model = YOLO('C:/Users/Admin/Documents/ultralytics/runs/detect/train12/weights/best.onnx')
   ```
## Directories
- [datasets/chequeinfo-2](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/tree/main/datasets/chequeinfo-2): This directory contains the dataset used for training and validation of the models. It include cheque images along with corresponding annotations or labels.

- [runs/detect](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/tree/main/runs/detect): This directory is typically used to store output from detection runs, including model weights, logs, and evaluation results.

## Notebooks and Scripts
- [Cheque_Object_Detection.ipynb](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/Cheque_Obeject_Detection.ipynb): Notebook for detecting cheque objects using machine learning models.
- [OCR.ipynb](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/OCR.ipynb): Notebook demonstrating Optical Character Recognition (OCR) techniques for extracting text from cheque images.
- [YOLOv8 Model Epochs Comparison.ipynb](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/YOLOv8%20Model%20Epochs%20Comparison.ipynb): Notebook comparing YOLOv8 model performance based on epochs.
- [YOLOv8 Model Version Comparison.ipynb](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/YOLOv8%20Model%20Version%20Comparison.ipynb): Notebook comparing different versions of the YOLOv8 model.

## Other Files
- [requirements.txt](https://github.com/lwq1023999/Automated-Cheque-Information-Extraction-and-Verification-Using-Machine-Learning/blob/main/requirements.txt): This file specifies the Python packages and dependencies required to run the notebooks and scripts in your project. It's used for managing project dependencies and can be used with tools like pip to install the necessary packages.

## Notes
- Ensure have the required hardware (GPU) while training deep learning models.
- Some notebooks may require specific configurations or paths to datasets.
