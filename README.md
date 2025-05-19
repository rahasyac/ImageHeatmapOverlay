# TileVision

TileVision is a Python project that uses deep learning to generate heatmaps highlighting object presence within an image. The image is broken into smaller tiles, and a pretrained VGG16-based model predicts the likelihood of an object (e.g., a cat) in each tile. These predictions are then combined into a heatmap to visually highlight important regions.

---

## Features

- Breaks images into tiles for localized analysis  
- Uses pretrained VGG16 convolutional base for feature extraction  
- Predicts object presence per tile using a classification model  
- Generates heatmaps from tile predictions to visualize hot spots  
- Supports regression model for bounding box prediction (optional)  
- Visualization with Matplotlib to display heatmaps  
- Saves heatmap as an image file for further use

---

## Installation

Make sure you have Python 3 and install dependencies:

```bash
pip install numpy opencv-python tensorflow matplotlib
```bash
python apply_heatmap.py --input your_image.jpg --output heatmap_output.jpg

