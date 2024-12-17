# Interpreting Video Models: TimeSFormer and 3D CNNs
This repository contains the code for visualizing and interpreting TimeSFormer (Transformer-based) and 3D CNN-based video models. The project focuses on understanding the inner workings of video action recognition models using attention rollout and Grad-CAM.

## Project Overview
### What the Project Does:
Visualizes attention maps from a TimeSFormer (Transformer-based model) pre-trained on Kinetics-400.
Applies Grad-CAM to a 3D CNN to interpret activation maps at various layers.
Highlights the differences in how Transformers and CNNs process spatio-temporal features.
### Techniques Used:
1. Attention Rollout: Shows how attention flows through layers in TimeSFormer.
2. Grad-CAM: Generates heatmaps to visualize class-specific regions in 3D CNN outputs.


## Files Included
### Notebooks:
1. CloudComputing_FinalProject.ipynb (Focuses on TimeSFormer attention visualization)
2. Gradcam_skyjaforritun.ipynb (Demonstrates Grad-CAM for CNN-based models)

## How to Use
1. Clone this repository:
```bash
git clone https://github.com/yourusername/Interpreting-Video-Models.git
cd Interpreting-Video-Models
```

2. Install dependencies (Not needed on Colab):
```bash
pip install -r requirements.txt (will be added soon)
Run the notebooks:
```

## Results
- TimeSFormer: Attention maps reveal how global relationships across frames are captured.
 -3D CNN: Grad-CAM heatmaps show the evolution of activations from edges to object-level features.

## Notes
- Pre-trained weights for TimeSFormer (Kinetics-400) were used but are not included due to their large size.
- The 3D CNN model is reused from a previous project.

## Future Work
- Implement additional interpretability techniques like Layer-wise Relevance Propagation (LRP).
- Test models on domain-shifted datasets.
