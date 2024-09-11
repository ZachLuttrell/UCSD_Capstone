# UCSD Capstone - Semantic Segmentation for Building Footprint Extraction

![example_output_2](https://github.com/user-attachments/assets/3f22cfac-4646-4512-a5f5-2c1252c10790)

## Project Overview

This repository contains various collections of work that make up the development and deployment process of my capstone project: building footprint extraction from satellite imagery using semantic segmentation. The project explores the use of deep learning to extract meaningful building footprint data from freely available satellite imagery, contributing to urban planning, humanitarian efforts, and the nonprofit sector.

To see the finalized application in action, visit the deployed version here: [Building Footprint Extraction App](https://building-footprint-extraction.streamlit.app/).

The deployment repository is hosted at: [Deployment Repo](https://github.com/ZachLuttrell/building_footprint_extraction).

---

## Summary

This project was designed with accessibility and cost-efficiency in mind. The semantic segmentation model was built using freely available Sentinel-2 imagery to ensure that a wide range of sectors, including humanitarian aid, non-profits, and NGOs, could utilize the system without incurring prohibitive costs. 

The system leverages a UNet-based deep learning model to automatically extract building footprints from satellite images, and the deployment is hosted using no-cost cloud services. While the current deployment meets the project's goals, the architecture is designed to be scalable for future demands, such as higher resolution imagery or additional features like regular retraining pipelines.

---

## Repository Contents

This repository is organized into several key directories:

### 1. **Submission Steps**
   - Contains documents and notebooks submitted for each phase of the capstone project, covering the entire workflow from data collection to model deployment.

### 2. **Model Training & Evaluation**
   - **Training**: Contains notebooks used to train the UNet model, including preprocessing, hyperparameter tuning, and model architecture exploration.
   - **Evaluation**: Includes notebooks for evaluating model performance, such as Dice Coefficient, Jaccard Index, and more, on validation and test datasets.

### 3. **Inference**
   - Contains a notebook that demonstrates how to use the trained model to make predictions on new satellite imagery. This includes image pre-processing, patching, and stitching operations for efficient model inference.

### 4. **Models**
   - Contains the trained model files in various formats (e.g., `.keras`, `.h5`), including the final UNet model used in the deployed app.

### 5. **Data Cleaning & Processing**
   - Contains scripts and notebooks used to clean, preprocess, and format the original SpaceNet 7 Challenge dataset for training the segmentation model.

---

## Data Sources

- **Original Dataset**: The original, unprocessed dataset can be found through the [SpaceNet 7 Challenge](https://spacenet.ai/sn7-challenge/).
- **Preprocessed Dataset**: My cleaned and preprocessed version of the dataset, which was used for model training, can be accessed here: [Google Drive Link](https://drive.google.com/drive/folders/1CppX4y9O3mS50kLT5zYhjTRMclhXwufr?usp=sharing).

---

For more details, refer to the deployment documentation in the deployment repository: [Deployment Repository](https://github.com/ZachLuttrell/building_footprint_extraction).
