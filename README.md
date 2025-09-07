Brain Tumor MRI Classification using CNN (PyTorch)

Description:
This notebook demonstrates a convolutional neural network (CNN) model for classifying brain MRI images into four categories: Glioma, Meningioma, Pituitary, and No Tumor. The project uses the publicly available Brain Tumor MRI Dataset from Kaggle.

Features:

Preprocessing of MRI images with resizing and normalization.

Custom CNN architecture with three convolutional layers, pooling, dropout, and fully connected layers.

Training using AdamW optimizer and CrossEntropyLoss.

Evaluation of the model on the test set with accuracy computation.

Visualization of random predictions to verify model performance.

Dataset:

Source: [Brain Tumor MRI Dataset on Kaggle](https://www.kaggle.com/datasets/deeppythonist/brain-tumor-mri-dataset)

Directory structure:

train/
    glioma/
    meningioma/
    pituitary/
    no_tumor/
test/
    glioma/
    meningioma/
    pituitary/
    no_tumor/

Run the notebook; training and evaluation are GPU-accelerated if available.

View sample predictions for verification.

Results:

The model trains over multiple epochs, reducing the training loss over time.

Test set accuracy and sample predictions are displayed in the notebook.

Note:

This notebook is optimized for Kaggle’s environment but can be adapted for local use by adjusting dataset paths and device settings.
