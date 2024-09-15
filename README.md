# Ai Wardroable Wizard

AI Wardroable Wizard is a cutting-edge application that leverages the Stable Diffusion model for clothing and wardrobe manipulation.

#### Overview
This project uses the Stable Diffusion model for image inpainting, allowing users to alter specific parts of an image with high precision. The process involves:

1. Input Images: Providing a real image and a corresponding masked image where the changes are desired.
2. Masking: Performing masking operations using OpenCV to prepare the input images.
3. Inpainting: Using Stable Diffusion for generating the output with prompt engineering.
4. Output: Receiving the modified image that reflects the desired changes.

#### Features
Stable Diffusion Inpainting: Utilize the power of Stable Diffusion to modify specific parts of an image.
* OpenCV Masking: Precision masking using OpenCV to define areas for alteration.
* Prompt Engineering: Customizable prompts to guide the inpainting process.
* Output Visualization: View the before and after images to see the transformation.

#### Getting Started
Prerequisites
Python 3.7+
Required Python packages: opencv-python, torch, transformers, diffusers
Stable Diffusion model weights (downloaded and available in your environment)
