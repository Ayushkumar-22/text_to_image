# Text_to_image
# Text-to-Image Generation using Stable Diffusion and Diffusers

This repository contains a Google Colab notebook demonstrating text-to-image generation using the Stable Diffusion model and the Diffusers library from Hugging Face.
# Stable Diffusion Text-to-Image Generation with Diffusers Library

This repository provides a step-by-step guide on using the **diffusers** library from Hugging Face to perform text-to-image generation using **Stable Diffusion** models. The notebook demonstrates the setup, installation, and usage of the diffusion models to generate high-quality images from text prompts.


Overview
The notebook covers the following:

## Contents

1. **Setup and Installation**
2. **Importing Libraries**
3. **PyTorch Version Check**
4. **Loading the Stable Diffusion Model**
5. **Generating Images with Text Prompts**
6. **Working with Parameters to Refine Image Generation**

## Requirements

- Python 3.7+
- `diffusers` (Hugging Face)
- `transformers`
- `torch` (with CUDA support for GPU acceleration)
- `accelerate`
- `matplotlib`

  To install the necessary libraries, run:

  pip install diffusers transformers torch accelerate matplotlib
  !pip install diffusers transformers torch accelerate matplotlib

Installation of necessary libraries (diffusers, transformers, accelerate).
Loading a pre-trained Stable Diffusion model.
Generating images from text prompts.
Experimenting with various parameters like num_inference_steps, height, width, num_images_per_prompt, and negative_prompt.
Getting Started
Open the notebook in Google Colab.
Run the cells sequentially to install dependencies, load the model, and generate images.
Modify the prompts and parameters to experiment with different image generations.

# Dependencies
diffusers
transformers
accelerate
torch
matplotlib
Pillow

# Usage

You can modify the prompt variable and the params dictionary in the notebook to generate different images with varying characteristics.

