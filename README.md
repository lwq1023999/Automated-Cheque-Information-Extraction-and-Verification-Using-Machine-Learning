# Automated Cheque Information Extraction and Verification Using Machine Learning

This repository contains code and notebooks for automating cheque information extraction and verification using machine learning techniques. The project focuses on detecting cheque objects, performing OCR (Optical Character Recognition), and utilizing YOLOv8 models for epoch and version comparisons.

## Requirements

To run the provided notebooks and scripts, ensure you have the following dependencies installed:

- Python 3.6+
- Jupyter Notebook or JupyterLab
- OpenCV
- pandas
- matplotlib
- PyTesseract (for OCR)
- YOLOv8 (or equivalent) for object detection

You can install the required Python packages using pip:

```bash
pip install pandas matplotlib pytesseract
```

## Notebooks and Scripts
Cheque_Object_Detection.ipynb: Notebook for detecting cheque objects using machine learning models.
OCR.ipynb: Notebook demonstrating Optical Character Recognition (OCR) techniques for extracting text from cheque images.
YOLOv8 Model Epochs Comparison.ipynb: Notebook comparing YOLOv8 model performance based on epochs.
YOLOv8 Model Version Comparison.ipynb: Notebook comparing different versions of the YOLOv8 model.

## Notes

Ensure that you have the required hardware (GPU) if training deep learning models like YOLOv8.
Some notebooks may require specific configurations or paths to datasets, modify them accordingly.
