# Enhancing-Synthetic-Image-Realism
This work focuses on improving the visual fidelity of synthetic images using controlled diffusion models, guided text prompts, and super-resolution techniques. Our approach aims to generate high-quality, realistic samples suitable for downstream tasks in computer vision and generative AI. Includes a modular pipeline with ControlNet integration and optimization strategies for faster processing.

## 🔧 Pipeline Overview

The following block diagram illustrates the core components of our pipeline:

![Pipeline Diagram](Assets/Proposed-Methodlogy.png)

**Pipeline Stages:**
- **Input**: Synthetic image or segmentation map  
- **ControlNet**: Edge, Depth, and Segmentation map along with Text-prompt guided image refinement  
- **Super-Resolution**: Second step for upscaling and photorealistic enhancement  
- **Output**: High-resolution, realistic image

- ## 🧪 Results Demonstration

Below are sample outputs comparing the original synthetic images with their enhanced versions:

| Input | Enhanced Output |
|-------|-----------------|
| ![input1](path_to_input1.png) | ![output1](Assets/Linkedin.png) |
| ![input2](path_to_input2.png) | ![output2](Assets/Linkedin-1.png) |
