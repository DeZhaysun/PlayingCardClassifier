# Cards 
## Overview
This project focuses on building an image classifier using PyTorch to detect playing cards. The model is trained to classify images of playing cards into different categories based on their suits and ranks.

## Built with
- Python
- PyTorch
- torchvision
- timm (for model architectures)
- NumPy
- pandas
- Matplotlib
- Jupyter Notebook

## Data
The dataset used in this project consists of images of playing cards categorized into different classes based on their suits and ranks. The dataset is structured following the directory convention expected by PyTorch's ImageFolder dataset class. Data from https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification.

## Model
The image classification model is built using PyTorch and leverages pre-trained architectures from the timm library. The final layer of the model is modified to accommodate the specific task of classifying playing cards. 

## Model Evaluation
The performance of the model is evaluated based on training and validation loss metrics. Here are the plots depicting the training and validation loss over epochs:


## Conclusion
The playing card classifier demonstrates promising results in accurately classifying playing cards into different categories. Further optimization and fine-tuning may be necessary to enhance its performance and generalization ability.

## Reference
https://www.youtube.com/watch?v=tHL5STNJKag