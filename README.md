# Fine-Tuned ResNet for Chest X-ray Image Classification with Grad-CAM Visualization

## Overview

This repository contains the code and models for fine-tuning a ResNet-based deep learning model for the classification of chest X-ray images using the National Institutes of Health (NIH) healthcare dataset. In addition, it includes the implementation of Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize and interpret the model's predictions, providing valuable insights into key regions of interest within the X-ray images.

## Dataset

The NIH chest X-ray dataset is a publicly available dataset comprising a large collection of chest radiographs, annotated with various thoracic findings, making it a valuable resource for training and evaluating chest X-ray classification models.

## Model Fine-Tuning

I have fine-tuned a ResNet-based model on this dataset to create a highly specialized image classifier. This process involved:

- Data preprocessing and augmentation to enhance the dataset's diversity and reduce overfitting.
- Training the ResNet model with custom healthcare data, resulting in a highly accurate classifier for chest X-ray images.

## Grad-CAM Visualization

In addition to classification, I implemented Grad-CAM for interpretability and visualization of the model's predictions. Grad-CAM highlights the regions in the X-ray images that contribute most significantly to the model's classification decision. This valuable feature helps medical professionals and researchers better understand the model's decision-making process.

## Usage

- To train and fine-tune the ResNet model on your own healthcare data, refer to the training scripts and Jupyter notebooks provided in this repository.
- To apply Grad-CAM to visualize model predictions on your own data, you can use the Grad-CAM code included here as a reference.

## Credits

If you find this repository helpful in your work, please consider giving credit by citing the relevant sources and contributors.

## Contact

For any questions, feedback, or collaboration opportunities, feel free to contact us at [vinitwaingankar@gmail.com].
