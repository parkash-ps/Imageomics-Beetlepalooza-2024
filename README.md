# BeetlePalooza 2024 - Image Classification & Grad-CAM Visualization

## Overview
This repository contains Python scripts for image classification and Grad-CAM visualization using deep learning models. The primary focus is on processing beetle images through feature extraction, classification, and visualizing feature importance using Grad-CAM.

## Features
- **Image Classification**: Uses a ResNet50 model to classify beetle images.
- **Feature Extraction**: Extracts feature vectors using a CLIP-based TreeOfLifeClassifier.
- **Grad-CAM Visualization**: Generates heatmaps to highlight important regions in the image used for classification.
- **Background Removal**: Implements GrabCut segmentation to remove backgrounds from images.

## Installation
Ensure you have Python 3.8+ installed. Then, install the required dependencies:
```bash
pip install pybioclip pyinaturalist torch torchvision matplotlib opencv-python Pillow requests numpy
```

## Usage
### 1. Classify an Image

### 2. Generate Grad-CAM Heatmap

### 3. Remove Background


## Example Output
- **Predicted Class**: Ground Beetle
- **Grad-CAM Heatmap**: Highlights key features in the image.
- **Background Removed Image**: Extracts the beetle from the background.

## License
This project is released under an This project is released under the [MIT License](LICENSE).


## Contributors
- Parkash Singh
- Blair Mirka
- Nathan Fox
- Alec White

## Acknowledgments
Special thanks to the Imageomics Institute and BeetlePalooza 2024 organizers for supporting this project.

