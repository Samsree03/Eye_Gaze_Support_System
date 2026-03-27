# Eye Gaze Support System

AI-Driven Communication and Assistive Control for Paralyzed Patients

## Overview

The Eye Gaze Support System is an AI-powered assistive solution designed to enable communication and control for paralyzed patients using eye gaze detection and  blink-based Morse code encoding. The system integrates multiple deep learning models to achieve accurate real-time detection and classification.

## Project Structure

Eye_Gaze_Support_System/ 
├── backend/ 
│ └── Project_Notebook.ipynb \# Main notebook containing full implementation

## Notebook Execution Flow

All implementation is inside:

Project_Notebook.ipynb

The notebook contains the following major sections:

1.  Inception Model Initialization and Test with Sample Image\
2.  Live Model Testing\
3.  Definition of Communication System -- Blink Detection\
4.  Communication System with Live Video Testing\
5.  Final Project Code: Blink and Gaze Detection with Respective Controls\
6.  Final Project Code -- Video Testing\
7.  Final Project Code -- Image Inference

## How to Execute the Full System

To run the complete integrated system:

1.  Open Project_Notebook.ipynb
2.  Run initial setup and model loading sections.
3.  Scroll to: "Final Project Code: Blink and Gaze Detection with Respective Controls"
4.  Execute all cells below this section sequentially.

This section contains the fully integrated pipeline combining: - Blink detection - Gaze detection - Morse encoding logic - Control system output

## System Components

### Gaze Detection Module

-   YOLOv8 for eye localization\
-   Inception-ResNet-v2 for gaze classification\
-   Approximately 90% gaze accuracy

Used for directional control and wheelchair navigation.

### Blink Detection Module

-   DETR for eye and face detection (approximately 95% accuracy)\
-   Fine-tuned ResNet-50 for blink classification (approximately 99%
    accuracy)

Blink Logic: - Short blink → Dot (.) - Long blink → Dash (-)

### Morse Code Communication System

-   Time-based encoding and decoding
-   Converts blink sequences into alphabets
-   Supports Alphabetical Mode and Emergency Mode

## Technologies Used

-   Python\
-   OpenCV\
-   PyTorch\
-   YOLOv8\
-   DETR\
-   ResNet-50\
-   Inception-ResNet-v2\
-   Jupyter Notebook

## Key Achievements

-   99% blink classification accuracy\
-   90% gaze detection accuracy\
-   Real-time integrated detection pipeline\
-   Assistive communication using AI

## Applications

-   Assistive technology for paralyzed patients\
-   AI-powered wheelchair control\
-   Human-computer interaction research\
-   Emergency communication systems

## Project Significance

This project demonstrates how deep transfer learning and real-time detection models can be integrated to build practical assistive healthcare systems. By combining blink-based Morse communication with gaze-based control, the system provides an intelligent and accessible solution for individuals with severe motor disabilities.
