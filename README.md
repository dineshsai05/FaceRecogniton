# Facial Recognition Model

This repository contains a **Facial Recognition** model utilizing **Siamese Network architecture** for facial verification. The implementation consists of two primary files:

## Files

1. **[Facial Verification - Part 1.ipynb](Facial%20Verification%20-%20Part%201.ipynb)**: 
   - This notebook is used to create the necessary datasets for training the model. It generates **Anchor** and **Positive** folders, which contain images captured using OpenCV (approximately 500 images in each folder), along with a **Negative** dataset sourced from [Labelled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/).
   
2. **[Face_recognition.ipynb](Face_recognition.ipynb)**: 
   - This notebook trains the Siamese model, saves it, and tests its performance on the verification task.

## Instructions

### Dataset Preparation

- Ensure that you run **Facial Verification - Part 1.ipynb** first to prepare the required datasets before proceeding to train the model.

### Training the Model

- For optimal performance, it is highly recommended to use a GPU for training the model, as it can significantly reduce training time (from approximately 1000 minutes). You can use platforms like **Google Colab** or any other cloud-based GPU service.

### How to Use

1. **Set up the Environment**: Make sure to install all the necessary dependencies.
2. **Dependencies**: Tensorflow, opencv
3. **Run the Notebooks**: Execute the cells in the notebooks in order, following the instructions provided within each notebook.
4. **Test the Model**: After training, utilize the functions provided in the second notebook to test the model's performance on unseen images.

## Acknowledgements

- The dataset for Negative images is sourced from the [Labelled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) database.
