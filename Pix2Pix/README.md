# Paired Image to Image Translation Using Pix2Pix

![image](https://github.com/developershutt/GANS/blob/main/Pix2Pix/output/epoch_63.jpg)

In 2016, Pix2Pix came and dominate the way we do image translation.
It uses Conditional Generative Adversarial Network to map an input image to target image.

Pix2Pix also introduced a different Discriminator which check whether a Patch of generated image is real/fake (named PatchGAN).

Architecture of Discriminator
![image](https://github.com/developershutt/GANS/blob/main/Pix2Pix/assets/discriminator.png)

And the generator was a U-Net architecture to learn the low level information to generate high quality output

Architecture of Generator
![image](https://github.com/developershutt/GANS/blob/main/Pix2Pix/assets/generator.png)

This code is taken from a tutorial on Pix2Pix from scratch by Developers Hutt on Youtube.
[![See the video for better explanation of code](https://img.youtube.com/vi/eeeai1OrnDI/0.jpg)](https://www.youtube.com/watch?v=eeeai1OrnDI)