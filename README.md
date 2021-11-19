# Brain-Tumor_2d-Unet-Model

# Brain Tumor
A brain tumor is a growth of abnormal cells that have formed in the brain.
There are two main types of tumors: cancerous also known as malignant and non- cancerous known as benign.
The central nervous system is made up of the brain as well as the spinal cord. It can affect the brain’s ability to work normally.
Tumors that start in the brain are called primary brain tumors.
Cancers that have spread to the brain from somewhere else in the body are called secondary brain cancers.

# Unet-Model
The Unet is convolutional network architecture for fast and precise segmentation of images.

In this project, a dataset is taken, containing the images and masks of the respective images showing brain tumor. Here we tried to predicted the correct mask for a particular image by training a 2-d unet model using 'Adam' optimizer with 'dice_loss' as loss function and also 'dice coefficient' as the metrics. For improving the accuracy and performance of the model we provided more data to the model by augmenting more data from the dataset given, and eventually adding the new generated data to the original dataset.
