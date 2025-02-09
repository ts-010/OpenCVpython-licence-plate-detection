# Automatic Number Plate Detection for Indian Vehicles  
### A Digital Image Processing Minor Project  

## 📌 Overview  
Automatic Number Plate Recognition (ANPR), also known as License Plate Recognition (LPR), is a crucial technology in smart city infrastructure and the Internet of Things (IoT). 
With the rapid increase in the number of vehicles, automated systems for vehicle identification and tracking have become essential for applications such as security, traffic monitoring, and parking management.  

This project focuses on developing an efficient and robust ANPR system tailored specifically for Indian vehicles, overcoming challenges such as non-standard fonts, varying lighting conditions, and diverse plate designs.  

## 🚀 Implementation  
The proposed system utilizes a series of **image processing techniques** to accurately detect and recognize vehicle number plates.  

### 🔹 **1. Preprocessing**  
- **Noise Reduction**: Gaussian smoothing and thresholding techniques are applied to remove unwanted noise.  
- **Edge Detection**: The Sobel edge detection method enhances the visibility of plate boundaries.  
- **Morphological Transformations**: Used to refine the plate area for accurate segmentation.  

### 🔹 **2. Segmentation & Character Extraction**  
- **Contour Detection**: Borders are identified using contour-finding algorithms.  
- **Filtering Techniques**: Non-character regions are eliminated based on predefined spatial and size constraints.  

### 🔹 **3. Character Recognition & Data Storage**  
- **Optical Character Recognition (OCR)** is applied to extract alphanumeric characters from the segmented plate.  
- **Database Storage**: The recognized text is stored for further processing, searching, and retrieval.  

## 📌 Applications & Future Scope  
✅ Small institutions, residential complexes, and apartment security gates for automated vehicle identification.  
✅ Potential enhancements for **Private office/residentical building entry, toll collection, and intelligent traffic management systems**.  
  
