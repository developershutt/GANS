# Unpaired Image to Image Translation Using CycleGAN

![image](https://github.com/developershutt/GANS/blob/main/CycleGAN/images/cyclegan.PNG)

[Apple2Orange Dataset](https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/apple2orange.zip)

It uses Cycle Consistent loss to learn the relationship between input and target image.

Architecture of Discriminator

![image](https://github.com/developershutt/GANS/blob/main/Pix2Pix/assets/discriminator.png)

And the generator was a U-Net architecture to learn the low level information to generate high quality output

Architecture of Generator

![image](https://github.com/developershutt/GANS/blob/main/Pix2Pix/assets/generator.png)

Outputs
![image](https://github.com/developershutt/GANS/blob/main/CycleGAN/output/output_151.jpg)
![image](https://github.com/developershutt/GANS/blob/main/CycleGAN/output/output_152.jpg)
![image](https://github.com/developershutt/GANS/blob/main/CycleGAN/output/output_153.jpg)

This code is taken from a tutorial on CycleGAN from scratch by Developers Hutt on Youtube. Watch it by clicking below

[![See the video for better explanation of code](https://img.youtube.com/vi/AsJ4jbxyens/0.jpg)](https://www.youtube.com/watch?v=AsJ4jbxyens)

# Credits
[Credit: Main source code](https://www.tensorflow.org/tutorials/generative/cyclegan)