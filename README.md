# Project: Efficient Deep Learning for Geospatial Image Classification
This project explores and evaluates memory-efficient image loading, data augmentation, and classification strategies using Keras and PyTorch. We work with the EuroSAT satellite imagery dataset to build and compare Convolutional Neural Networks (CNNs), Vision Transformers (ViTs), and hybrid models for land use classification.

## Project Structure
The repository is organized into nine Jupyter notebooks, corresponding to the nine tasks of the project.

|-- M1_01_Memory_vs_Generator_Loading.ipynb
|-- M1_02_Keras_Data_Augmentation.ipynb
|-- M1_03_PyTorch_Data_Augmentation.ipynb
|-- M2_04_Keras_CNN_Classifier.ipynb
|-- M2_05_PyTorch_CNN_Classifier.ipynb
|-- M2_06_Keras_vs_PyTorch_Comparison.ipynb
|-- M3_07_Keras_Vision_Transformer.ipynb
|-- M3_08_PyTorch_Vision_Transformer.ipynb
|-- M3_09_CNN_Transformer_Integration.ipynb
|-- requirements.txt
|-- README.md

## How to Use
## 1. GitHub Submission
You can clone this repository or download the files and upload them to your own GitHub repository for submission.

## 2. Running in Google Colab
For each .ipynb file, follow these steps to run it in a free cloud environment:

Open Google Colab.

Go to File -> Upload notebook.

Select one of the project's .ipynb files from your computer.

Once the notebook is open, you can run the cells one by one. The first code cell in each notebook will install the necessary libraries.

Make sure to enable a GPU for faster training by going to Runtime -> Change runtime type -> Hardware accelerator -> GPU.

## 3. Running Locally
Clone the repository.

Install the required libraries:

pip install -r requirements.txt

Launch Jupyter Notebook or JupyterLab and open the .ipynb files.

## Project Modules
### Module 1: Data Loading & Augmentation
Notebook 1: Compares memory-based vs. generator-based data loading techniques.

Notebook 2: Implements a high-performance data pipeline with augmentation in Keras.

Notebook 3: Implements a high-performance data pipeline with augmentation in PyTorch.

### Module 2: CNN-Based Classification
Notebook 4: Builds, trains, and evaluates a CNN classifier using Keras.

Notebook 5: Builds, trains, and evaluates a CNN classifier using PyTorch.

Notebook 6: Provides a comparative analysis of the Keras and PyTorch models.

### Module 3: Advanced Models
Notebook 7: Implements and evaluates a Vision Transformer (ViT) in Keras.

Notebook 8: Implements and evaluates a Vision Transformer (ViT) in PyTorch.

Notebook 9: Builds and evaluates a hybrid CNN-Transformer model for land classification.
