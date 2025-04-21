# 🐶🐱 Pet Breed Classification Case Study

This project classifies 35 breeds of dogs and cats using deep learning and transfer learning. It uses the Oxford-IIIT Pet Dataset and applies a fine-tuned ResNet-50 model for high-accuracy breed identification.

---

## 📚 Context

Before doing anything, read the 2 files:
- [`CS3HookDocument.pdf`](https://github.com/AnvithaB04/CS3-DS4002/blob/main/CS3HookDocument.pdf): Provides background on what this case is about  
- [`CS3Rubric.pdf`](https://github.com/AnvithaB04/CS3-DS4002/blob/main/CS3Rubric.pdf): Outlines what is required for this assignment
---

## 📂 Documentation

### Articles folder
Contains references contextualizing the project:
- `blog_intro_to_transfer_learning.pdf`: Beginner-friendly overview of transfer learning 
(Understanding Transfer Learning for Deep Learning)

- `deep_resnet_paper.pdf`: Detailed explanation of the ResNet50 CNN architecture
(Medium: Detailed Explanation of ResNet50)

### Data folder
- `DataAppendix.pdf`: Overview of dataset contents, variables, processing steps
- `Data Instructions.pdf`: Explains how to download and organize the dataset

### Reference Materials
- `CS3HookDocument.pdf`: One-page overview of the project
- `CS3Rubric.pdf`: Submission guidelines and evaluation rubric

### Scripts folder
- `Model_Training_and_Evaluation.ipynb`: Full Colab notebook for model training/evaluation
- `data_organization.py`: Sorts raw images into breed folders
- `data_preprocessing.py`: Resizes, normalizes, and augments images for training
- `requirements.txt`: Lists all necessary Python packages and versions required to run the scripts
---

## ⚙️ Producing Results

The most straightforward way to conduct the analysis is through using Google Colab, which provides access to powerful GPUs and has many of the necessary libraries pre-installed. You are welcome to use VS Code or Jupyter Notebook on your local machine; however, you will likely need to install the packages listed in requirements.txt.

To produce the results of this project, first read and follow the instructions in the Data Instructions PDF located in the Data/ folder. This document outlines how to download the Oxford-IIIT Pet Dataset, organize the raw images into breed-specific folders using a Python script, and preprocess the images by resizing, normalizing, and augmenting them. Once these steps are complete, upload the resulting organized_images folder to your Google Drive.

Next, open the file Model_Training_and_Evaluation.ipynb located in the SCRIPTS/ folder using Google Colab. You will need to mount your Google Drive and update the file paths in the notebook to point to the uploaded organized_images directory. Once set up, run the notebook from top to bottom to load the data, train a ResNet-50 model using transfer learning, evaluate its performance, and generate output visualizations.
