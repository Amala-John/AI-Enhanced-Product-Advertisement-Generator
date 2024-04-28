# AI-Enhanced-Product-Advertisement-Generator
This Data Science solution utilizes image generative AI models to create high-quality advertisement images for various products. The goal is to produce aesthetically pleasing outputs while prominently featuring the brand name and product without compromising quality.

Input
Product images with white backgrounds are provided in the input_product folder. Additionally, background images or text prompts are required to generate background images. You need to provide these yourself.
Output
Generate 5 output images for each product image with different backgrounds. A total of 25 images should be generated.
# Image Inpainting with Diffusers and REMBG


This repository contains code to perform image inpainting using Diffusers and REMBG.

The generated output images should resemble professional advertisements, featuring clearly visible brand names and images with seamless merging of product images with backgrounds.

## Requirements

Make sure you have the following dependencies installed:

- `rembg`
- `accelerate`
- `diffusers==0.24`
- `torch`
- `numpy`
- `PIL`
You can install them using pip:

## Features
Generates 5 output images for each product image with different backgrounds.
Utilizes a variety of background images or text prompts to enhance output.
Ensures brand names and product images are clearly visible in the output images.
Provides seamless merging of product images with backgrounds.
Capable of generating output images in under 10 minutes.
## Usage
Place product images in the input_product folder.
Provide background images or text prompts for generating background images.
Run the script to generate output images:
Output images will be saved in the output_images folder.
##Solution Details
Model/Framework: This project utilizes different stable diffusion inpainting models for image generation.
Approach: The solution employs a combination of pre-trained models and custom modifications to ensure high-quality output images. Background images or text prompts are carefully selected to enhance the aesthetic appeal of the advertisements while prominently featuring the product and brand name.

