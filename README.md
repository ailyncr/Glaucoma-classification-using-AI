# Glaucoma-classification-using-AI

## Image Classification with CNN

This project implements a convolutional neural network (CNN) to classify glaucoma images into three categories: Normal, Early, and Advanced. The model uses Conv2D layers with L2 regularization, MaxPooling2D, and Dropout to reduce overfitting, achieving an accuracy of 77.18%. Training metrics such as accuracy and loss are monitored and visualized.

### Project Structure

```
├── Notebook/                  # Jupyter notebooks
├── Reporte/                # Report based on the model and results
└── README.md
```
### Dataset

https://doi.org/10.7910/DVN/1YRRAC

This project uses a public dataset from the Harvard Dataverse, an online repository that provides access to a wide range of datasets. The dataset consists of retinal images, including samples from healthy individuals as well as patients diagnosed with glaucoma.

To use the dataset, download it from Harvard Dataverse and organize it into the following folder structure:

```
Dataset/
├── Normal/
├── Early/
└── Advanced/
```
Each folder should contain the corresponding retinal images for that classification.
