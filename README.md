# Graphical Content Recognition with Editable Charts and Layout Retention

## Overview

This project aims to convert static graphical documents into editable formats such as SVG and DOCX while preserving their original layout and structure. It detects and processes various elements like text, tables, bar graphs, and pie charts using machine learning models. The extracted elements remain editable and retain the original page dimensions.

## Features

-   **Text Detection & Recognition**: Uses PaddleOCR for extracting and recognizing textual content.
    
-   **Table Detection & Reconstruction**: Converts tables into editable formats.
    
-   **Bar Graph Recognition**: Detects bars using Detectron2 and extracts bar dimensions and text labels.
    
-   **Pie Chart Recognition**: Uses PaddleOCR and image processing to reconstruct pie charts.
    
-   **Layout Retention**: Maintains the original document structure and dimensions.
    
-   **Editable Output**: Generates interactive and editable output files.
    

## Technologies Used

-   **Detectron2 (R50_FPN_3x model)**: Object detection for document layout analysis.
    
-   **PaddleOCR**: Text detection and recognition.
    
-   **TensorFlow**: Model optimization and preprocessing.
    
-   **OpenCV**: Image preprocessing and feature extraction.
    
-   **Matplotlib**: Chart visualization and synthetic dataset creation.
    
-   **ReportLab**: PDF generation with reconstructed elements.
    




## Usage

1.  Upload an image or document.
    
2.  The system detects and extracts graphical and textual content.
    
3.  Edit the detected elements via the interactive GUI.
    
4.  Export the modified document with preserved layout.

## Results

### Initial Image Classification<br>

### Bar Graph

### Pie Chart 

### Table 

### Classification Loss 

### Final Output PDF
    

