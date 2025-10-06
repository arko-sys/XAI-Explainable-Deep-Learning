Explainable Deep Learning with GradCAM and its variants

This repository contains a Jupyter Notebook that demonstrates the use of GradCAM and its variants (GradCAM++ and ScoreCAM) to explain predictions made by a pretrained ResNet-50 model on an animal image classification task. The notebook visualizes class activation maps (CAMs) and analyzes how different methods highlight regions of interest in input images.

Repository Structure
.
├── README.md              # Instructions (this file)
├── requirements.txt       # Python dependencies
├── data/                  # Place dataset folders here
│   ├── class1/            # e.g., dolphin/
│   │   ├── img1.jpg
│   │   └── img2.jpg
│   └── class2/            # e.g., panda/
├── outputs/               # Generated CAM visualizations (saved as .png)
└── explainable_cam.ipynb  # Main notebook

Setup

Clone the repository

git clone https://github.com/yourusername/explainable-cam.git
cd explainable-cam

