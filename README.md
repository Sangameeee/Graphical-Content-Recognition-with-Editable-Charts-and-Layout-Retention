# Graphical Content Recognition with Editable Charts and Layout Retention
## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Results](#results)
  
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

### 1. Initial Image Classification<br>
![Mobile Screenshot](https://github.com/Sangameeee/Graphical-Content-Recognition-with-Editable-Charts-and-Layout-Retention/blob/main/images/intial%20image.png?raw=true)
### 2. Bar Graph
![Mobile Screenshot](https://github.com/Sangameeee/Graphical-Content-Recognition-with-Editable-Charts-and-Layout-Retention/blob/main/images/bar_graph.png?raw=true)
### 3. Pie Chart 
![Mobile Screenshot](https://github.com/Sangameeee/Graphical-Content-Recognition-with-Editable-Charts-and-Layout-Retention/blob/main/images/pie_chart.png?raw=true)
### Table 
![Mobile Screenshot](https://github.com/Sangameeee/Graphical-Content-Recognition-with-Editable-Charts-and-Layout-Retention/blob/main/images/table_image.png?raw=true)
### 4. Classification Loss 
![Mobile Screenshot](https://github.com/Sangameeee/Graphical-Content-Recognition-with-Editable-Charts-and-Layout-Retention/blob/main/images/classi_loss.png?raw=true)
### 5. Final Output PDF
![Mobile Screenshot](https://github.com/Sangameeee/Graphical-Content-Recognition-with-Editable-Charts-and-Layout-Retention/blob/main/images/final_image.png?raw=true)
