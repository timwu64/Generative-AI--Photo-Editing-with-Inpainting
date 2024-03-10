# Generative-AI--Photo-Editing-with-Inpainting

## Project Overview

This project demonstrates the application of advanced AI techniques in photo editing, specifically focusing on object segmentation and inpainting. Utilizing the Segment Anything Model (SAM) and pretrained models from the diffusers library, the project showcases how to seamlessly segment subjects from images and perform inpainting to substitute backgrounds or subjects with desired scenes or elements.

### Features

- **Segmentation**: Implementing the SAM to accurately segment subjects from a variety of images.
- **Inpainting**: Utilizing a pretrained AutoPipelineForInpainting model to creatively alter image backgrounds.
- **Interactive App**: An interactive application that allows users to experiment with segmentation and inpainting in real-time.

### Segment the Subject

- **Objective**: Demonstrate proficiency in loading and using the SAM to segment objects.
- **Specifications**: Completion of the SAM section by accurately segmenting objects, with the output resembling the provided example.

### Inpainting

- **Objective**: Show proficiency in loading and using a pretrained AutoPipelineForInpainting model.
- **Specifications**: Successful alteration of images by substituting backgrounds with a Mars landscape, demonstrating a grasp of inpainting techniques.

### Interactive App

- **Objective**: Utilize the interactive app to demonstrate understanding of the end-to-end process.
- **Specifications**: Proper use of the app to segment subjects and substitute backgrounds or subjects, with documented results through screenshots or uploaded images.

## Getting Started

1. **Prerequisites**: Ensure you have Python installed along with the necessary libraries: PIL, requests, transformers, diffusers, torch, numpy.
2. **Installation**:
   - Clone this repository.
   - Install the required dependencies using `pip install -r requirements.txt`.

3. **Running the Project**:
   - Execute the Jupyter Notebook `AI_photo_editor_with_stable_diffusion_and_SAM_model.ipynb` to explore the functionalities.
   - Follow the instructions within the notebook to segment subjects and perform inpainting tasks.
   - Launch the interactive app as directed in the notebook to test the features with your own images.
