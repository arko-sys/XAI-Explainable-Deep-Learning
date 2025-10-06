# Explainable Deep Learning with GradCAM and Variants

This repository contains a Jupyter Notebook that demonstrates the use of **GradCAM** and its variants (**GradCAM++** and **ScoreCAM**) to explain predictions made by a pretrained **ResNet-50** model on an animal image classification task. The notebook generates and visualizes class activation maps (CAMs) to analyze how different explainability methods highlight regions of interest in input images.

---

## Setup

Clone the repository and navigate into it:

```bash
git clone https://github.com/yourusername/explainable-cam.git
cd explainable-cam
```

## Usage

1. Run through the notebook cells to:
   - Load a pretrained ResNet-50 model.  
   - Apply GradCAM, GradCAM++, and ScoreCAM.  
   - Generate and save visual explanations in the `outputs/` directory.

---

## Outputs

- All generated CAM visualizations will be stored in the `outputs/` folder as `.png` files.  
- Example outputs include heatmaps overlaid on input animal images.

