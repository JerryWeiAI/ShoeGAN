# Using Generative Adversarial Networks to Generate New Shoe Designs

This code used GANs to generate new shoe designs. The code is based off of Siraj's pokeGAN code which can be found [here](https://github.com/llSourcell/Pokemon_GAN).

I created two models that I trained on different datasets. Version 1 is trained on shoes that were scraped off of Zappos, while Version 2 is trained on shoes that were scraped off of Amazon. The shoes from Zappos were formatted with one shoe in front and one shoe in the back of the image, while the shoes from Amazon were only one shoe at a slight angle. 

Version 2's Generated Shoe Designs After 500 Epochs:

![](https://github.com/JerryWei03/ShoeGAN/blob/master/epoch500v2.jpg)

Version 1's Generated Shoe Designs After 100 Epochs:

![](https://github.com/JerryWei03/ShoeGAN/blob/master/epoch99v1.jpg)
