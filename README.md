# FaceGenerator
A GAN that generates 32x32 faces using the celebrity face dataset

# Summary
This model creates some uncanny valley type faces. It could certainly use some more training, but it stands as a proof of concept.
You'll notice that there also seems to be some smearing of facial features in the sample output. My hunch is that the model may
need more training *and* more convolutional layers to better detect the structure of faces.

# Future Work
It would be exciting to see this model output faces at a higher resolution than the input (e.g. 64x64 images from the 32x32 img
dataset). This can be done by changing the transpose convolution layers, but it would require re-training the model and probably
some other reworks as well.
