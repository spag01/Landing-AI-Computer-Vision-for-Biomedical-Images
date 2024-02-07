# Landing-AI-Computer-Vision-for-Biomedical-Images
This project is my contribution to the bigger project where each of the group members supposed to work on a Biomedical Images dataset. We decided to train different computer vision models for different datasets using Landing AI. The models later were deployed and tested on validation set. Here is my work: 

## For classification.ipynb
### Overview
This code repository is designed for breast cancer image classification using Landing AI's model. It includes scripts for dataset creation, model inference, and validation. The dataset consists of benign, malignant, and normal breast tissue images.

### Setup
1. Install the required dependencies
2. Download the dataset:
  - The dataset will be automatically downloaded from Google Drive.
3. Run dataset preparation:
  - Randomly select images for a validation set from the dataset to assess model accuracy.
4. Configure Landing AI model:
  - Replace deployed_model_endpoint and _api_key with your Landing AI model details.
  
### Running the Code
Dataset Preparation:
- Execute the dataset preparation script to create a validation set.
2.Landing AI Inference:
- Run Landing AI model inference on the validation set and calculate accuracy.
  
### Folder Structure
- data/CMPT340_Project: Main project folder.
  - BreastCancerDataset: Original dataset.
- dataset-classification: Processed dataset for model training.
  - validation: Validation set for accuracy assessment.
- dataset-classification-overlayed: Dataset with overlayed masks for visual inspection.
  - validation: Overlayed validation set.

### Usage Notes
- Ensure proper configurations for Landing AI model (deployed_model_endpoint and _api_key).
- Adjust validation set sizes and other parameters as needed.

### Note
- The code suppose to dowload the "data" folder saved in the Google drive. But here I have already provided the contents of data folder so the first two cells code can be skipped.
- For manually categorizing dataset based on the classification model- Please refer helping file imagesFilter.ipynb notebook. 

