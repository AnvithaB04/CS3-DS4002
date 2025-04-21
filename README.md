# 🐶🐱 Pet Breed Classification Case Study

This project classifies 35 breeds of dogs and cats using deep learning and transfer learning. It uses the Oxford-IIIT Pet Dataset and applies a fine-tuned ResNet-50 model for high-accuracy breed identification.

---

## 📚 Context

Before doing anything, read the 2 files within the **Reference Materials** folder:
- `CS3 Hook Document.pdf` provides background on what this case is about
- `CS3 Rubric.pdf` outlines what is required for this assignment

---

## 📂 Documentation

### Articles folder
Contains references contextualizing the project:


### Data folder
- `DataAppendix.pdf`: Overview of dataset contents, variables, processing steps
- `data_instructions.txt`: Explains how to download and organize the dataset

### Reference Materials
- `CS3 Hook Document.pdf`: One-page overview of the project
- `CS3 Rubric.pdf`: Submission guidelines and evaluation rubric

### Scripts folder
- `Model_Training_and_Evaluation.ipynb`: Full Colab notebook for model training/evaluation
- `data_organization.py`: Sorts raw images into breed folders
- `data_preprocessing.py`: Resizes, normalizes, and augments images for training

### Output folder
- `accuracy_loss_plot.png`: Training and validation curves
- `confusion_matrix.png`: Final confusion matrix

---

## ⚙️ Producing Results

**Step 1: Download Data**
- Go to [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/)
- Download `images.tar.gz` and extract into `Data/InputData/images/`

**Step 2: Organize and Preprocess**
```bash
python Scripts/data_organization.py
python Scripts/data_preprocessing.py
