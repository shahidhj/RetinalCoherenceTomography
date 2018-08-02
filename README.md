# Retinal optical Coherence Tomography
Retinal optical coherence tomography (OCT) is an imaging technique used to capture high-resolution cross sections of the retinas of living patients. The images are divided into four categories - **Drusen, Coherence Neo Vascular(CNV) ,Diabetic Macular Edema(DME)** which are the diffrent kinds of damages caused to the retina and the fourth category being a normal image of an eye. This project uses [fast.ai] library(https://github.com/fastai/fastai) which is built on top of PyTorch.Around 85000 images were used to train and validate the neural network. The architecture consists of a pre-trained network(**Resnet34**) and accuracy obtained is 93.84%.Training for additional epochs would increase the accuracy.


