Melanoma-Image-Recognition

The dataset is from kaggle and is a collection of 11000 images of benign and malignant moles. 


The following CNN model was made using Pytorch.
The images were initally 300 by 300 pixel but were resized  to 100 by 100 due to system limitations.
The CNN consists of 3 convolutional layers then flattens into two dense layers with binary outputs. Data is labelled with one hot encoding- [1,0] being begign and [0,1] being malignant.
While tuning we determined the ideal parameters of a batch size of 16 and 15epochs.
through this we achieved an accuracy of 0.94
