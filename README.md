# Monet_Cycle_GAN
Kaggle Competition: https://www.kaggle.com/c/gan-getting-started

## Challenge: 

A GAN consists of at least two neural networks: a generator model and a discriminator model. The generator is a neural network that creates the images. For our competition, you should generate images in the style of Monet. This generator is trained using a discriminator.

The two models will work against each other, with the generator trying to trick the discriminator, and the discriminator trying to accurately classify the real vs. generated images.

Your task is to build a GAN that generates 7,000 to 10,000 Monet-style images.

## Solution:

I proposed a Cycle GAN architecture for this problem. Although it achieves a public score of MiFID = 107.82630 on the leaderboard, I think with data Augmentation can improve this model's output. 

Feel free to play with the no. of epochs and see the result.

Suggestions are welcome.

## Output:

After running every cell, you will have a images.zip folder having 7030 images of the photos with monet's style.
