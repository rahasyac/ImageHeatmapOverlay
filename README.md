# Heatmap Overlay for Image Analysis

## Project Overview
This project applies a heatmap overlay to highlight key areas of an image while ensuring smooth blending and minimal noise. The goal is to create a visually meaningful and accurate heat map representation.

## Features
- Highlights meaningful areas of interest using a heatmap.  
- Ensures smooth edges without harsh noise.  
- Balances blending to avoid overpowering or fading.  
- Maintains image clarity and visual appeal.

## How It Works
1. Load the image – The input image is processed.  
2. Generate the heatmap – The heatmap is applied based on computed intensity regions.  
3. Blend the overlay – The heatmap is integrated smoothly with the original image.  
4. Final enhancements – Noise is reduced, blending is adjusted, and edges are refined.  

## Installation & Usage
### Prerequisites
- Python 3.x  
- OpenCV (`pip install opencv-python`)  
- Matplotlib (`pip install matplotlib`)  
- NumPy (`pip install numpy`)  

### Run the Code
```bash
python apply_heatmap.py --input your_image.jpg --output heatmap_output.jpg

