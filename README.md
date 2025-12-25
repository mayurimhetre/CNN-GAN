# GAN for Flower Image Generation

## Overview
This project demonstrates the use of **Generative Adversarial Networks (GANs)** to generate realistic images of flowers. GANs are a type of deep learning model where two neural networks, a **generator** and a **discriminator**, compete against each other to produce new, synthetic images that resemble real ones.

## Dataset
The dataset contains images of various flowers. The images are used to train the GAN so that the generator learns to create realistic flower images.

## Objective
The main goal is to generate **new flower images** that are visually similar to the real ones in the dataset. This involves training the GAN until the discriminator cannot easily distinguish between real and generated images.

## Approach
1. **Generator**: Produces new flower images from random noise.  
2. **Discriminator**: Evaluates whether an image is real or generated.  
3. **Training**: Both networks are trained in a loop, improving the generator’s ability to create realistic images and the discriminator’s ability to detect fakes.

## Outcome
After training, the generator can produce **synthetic flower images**, showcasing the power of GANs in image generation tasks.
