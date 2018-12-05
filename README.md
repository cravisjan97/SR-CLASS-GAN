# SR-CLASS-GAN
A novel Deep Learning model which combines the tasks of Super Resolution and Classification

Classifying low-resolution images is one of the challenging tasks in deep learning. Usually, a low-resolution image is super-resolved to a high-resolution image and is then classified to improve the classification accuracy. We proposed a novel deep learning model SR-CLASS-GAN: a generator discriminator architecture which combines the tasks of super-resolution and classification in a single model. Usually, a discriminator determines whether the input image to the discriminator is real or fake. But in our SR-CLASS-GAN model, the discriminator not only determines whether the image is real or fake but also classifies the image. Through various experiments, we have significantly reduced the number of parameters and training time while producing state of the art results.

The SR-CLASS-GAN model can be summarized by the following figure:
![SR-CLASS-GAN](/writeup/SR-CLASS-GAN.jpg)

The Generator and Discriminator architecture used are:
![Generator Architecture](/writeup/Generator.jpg) ![Discriminator Architecture](/writeup/Discriminator.jpg)

The results of our model are:
![Results](/writeup/Table.png)

