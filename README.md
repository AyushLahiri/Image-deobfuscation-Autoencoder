# Image-deobfuscation-Autoencoder

5 March 2020 
This study aims to reconstruct obfuscated facial and demonstrates that modern image recognition methods based on neural networks can recover hidden in-formation from images. I have used a convolutional auto-encoder that takes noisy, pixelated, or blurred
images as input and attempts to re-construct recognizable facial images. 
We create training datasets using Umass Amherst's ["Faces in the wild"](http://vis-www.cs.umass.edu/lfw/) Dataset. We introduce pixelation, speckle noise and gaussian blur to these images to create our input data and use the original images as our output label.
For training, pixel, perceptual and a weighted combination of the two have been used as loss functions.
The results demonstrate that our trained model can successfully reconstruct facial images
from highly obfuscated images, with some limitations in clarity, relative to the ground
truth
Please refer to the [final report](https://github.com/AyushLahiri/Image-deobfuscation-Autoencoder/blob/main/Report.pdf) for a detailed summary of the project. 
