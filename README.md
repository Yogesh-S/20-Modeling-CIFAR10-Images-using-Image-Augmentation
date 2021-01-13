# Image-Augmentation

Our CNN model should learn invariant representation of image.

We do not want our model to change its prediction based on
1. Size of object - Scale invariance
2. Angle of object - Rotation invariance
3. Object shift - Translation invariance

To overcome this we do data augmentation

1. Flipping: flipping the image vertically or horizontally
2. Rotation: rotates the image by a specified degree.
3. Shearing: shifts one part of the image like a parallelogram
4. Cropping: object appear in different positions in different proportions in the image
5. Zoom in, Zoom out
6. Changing brightness or contrast

In this notebook, we have limited to just two simple transforms - random horizontal flip, random rotation by 10°

![alt text](https://github.com/Yogesh-S/20-Modeling-CIFAR10-Images-using-Image-Augmentation/blob/main/image_augment.png?raw=true)
