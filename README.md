# 🚘 Number Plate Recognition Using Deep Learning

This project implements a system for detecting and recognizing **vehicle number plates** from images using bounding box annotations and a custom CNN model. The system can identify license plates in images and extract textual information using **Optical Character Recognition (OCR)**.

---

## 🌟 Project Highlights

- **Data Preprocessing**: Extracted bounding boxes for license plates from annotated XML files. 🖼️
- **Custom CNN Model**: Designed a CNN for bounding box regression and feature extraction. 🤖
- **OCR Integration**: Incorporated **Tesseract OCR** to recognize text from extracted plate regions. ✍️
- **Visualization**: Plotted bounding boxes on detected number plates for analysis. 📊

---

📊 **Data Overview**

Dataset:

Images with bounding box annotations for license plates in XML files.

Bounding Box Format: xmin, xmax, ymin, ymax

Output: Detected license plate regions and recognized text.

🤖 **Model Details**

Architecture:

Input Layer: 128x128 grayscale image.

Convolutional Layers: Four convolutional layers with ReLU activation.

Pooling Layers: Max pooling layers for down-sampling.

Dense Layers: Fully connected layer for bounding box regression.

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam
