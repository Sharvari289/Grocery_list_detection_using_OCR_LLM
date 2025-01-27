# Grocery App

## Overview
The **Grocery App** is a tool for processing images of handwritten or printed grocery item lists. It extracts, recognizes, and organizes the text in the image into a structured format using Optical Character Recognition (OCR) and **Large Language Model (LLM)**-powered refinement. The application includes a user-friendly interface built with **Streamlit** for easy interaction and customization.

---

## Features
- **Image Upload**: Upload handwritten or printed grocery lists in image formats like JPG, PNG, etc.
- **Thresholding Methods**: Supports Adaptive, Normal, and Otsu thresholding for image preprocessing.
- **Bounding Box Visualization**: Option to display bounding boxes around detected text.
- **Text Recognition**: Recognizes text using a trained deep learning model.
- **Text Correction and Refinement**: Standardizes and structures extracted text into a `[item, quantity, unit]` format using an **LLM (Large Language Model)** powered by **Groq's Llama 3 model**.
- **Customizable Parameters**: Adjust contour area and threshold values to optimize recognition performance.

---

## Prerequisites
Before running the application, ensure you have the following installed:
- **Python 3.8+**
- **Streamlit**
- **TensorFlow**
- **OpenCV**
- **NumPy**
- **Pillow**
- **Groq Client SDK**

---


