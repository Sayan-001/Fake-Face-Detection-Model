# Fake-Face-Detection-Model
## Model

This is a Machine Learning Model that uses Convolutional Neural Networks (CNN) to detect between real images and fake images. 

Real: The photo is actually taken and the person exists.

Fake: The person does not exist and the images are generated using the StyleGAN2, i.e., AI generated.

The images look almost identical and indistinguishable to the human eye which makes it an extremely dificult task, but CNN can detect the slightest of changes, and give a very accurate prediction, of whether the image is 'real' or 'fake'.

The model is trained on the Train Dataset, and evaluated using Validation Dataset. The test Dataset is kept for the user to put and check.


## Dataset

The dataset can be found here: [click here for Google Drive link](https://drive.google.com/drive/folders/15QFBLT2GHWW1nDPj6KwgGiG6auOlZe7T?usp=drive_link).

It consists of closely 1200 real and fake images, with uniform pixel dimensions of 300 x 300, divided into Train, Validation and Test Dataset in 90%-8%-2% (approx.) format.

Real:

![Real Image 1](Images/real_81.jpg)
![Real Image 2](Images/real_460.jpg)

Fake:

![Fake Image 1](Images/fake_114.jpg)
![Fake Image 2](Images/fake_118.jpg)

## Evaluation

The model has a validation accuracy of 100% and validation loss of 0.01.

Below is the graph of the accuracy and loss plotted against epochs (number of times the model is run).

![Image in Folder](Images/accuracy_loss_img.png)



