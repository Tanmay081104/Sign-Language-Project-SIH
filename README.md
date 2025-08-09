# Sign Language Project - SIH

## AI-Powered Sign Language Recognition System

This project implements an advanced computer vision system for real-time sign language recognition using deep learning techniques.

### Features
- Real-time sign language detection and classification
- CNN-based model with 8 groups for efficient processing
- Data collection tools for training dataset expansion
- Binary and multi-class classification support
- Interactive prediction interface

### Files Overview
- `final_pred.py` - Main prediction module with GUI interface
- `prediction_wo_gui.py` - Command-line prediction tool
- `data_collection_binary.py` - Binary classification data collection
- `data_collection_final.py` - Final data collection implementation
- `cnn8grps_rad1_model.h5` - Trained CNN model (13.5MB)
- `AtoZ_3.1/` - Dataset directory with A-Z sign language images

### Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- Deep Learning (CNN)
- Computer Vision

### Model Architecture
- 8-group CNN with radial basis functions
- Optimized for real-time performance
- High accuracy on sign language classification

### Setup Instructions
1. Install required dependencies:
   ```bash
   pip install tensorflow opencv-python numpy matplotlib
   ```
2. Run the main prediction interface:
   ```bash
   python final_pred.py
   ```
3. For command-line prediction:
   ```bash
   python prediction_wo_gui.py
   ```

### Dataset
The project uses a comprehensive A-Z sign language dataset with thousands of images per letter for robust training.

Developed for Smart India Hackathon (SIH) 2025
