# Image-Super-Resolution
---

Start with an image dataset and "crappify" the images, such as reducing the resolution, adding artifacts, and obscurring parts with random text. Then train a model to "decrappify" the images to return to their original state.

---


* The general adversarial network was invented by Ian Goddfellow, where two networks play a game. In our case, we will build a "crappifier" to make images worse, and the critic will try to determine which is fake and which is original. This will help us achieve super resolution.

* Let's build a function first that will go through and "crappify" some data

* And now lets get some data to work with we will use PETS dataset

* we'll make two folders, one for the low resolution and high resolution photos

* Now lets generate our dataset

* The goal of this model will be to generate our "super resolution" images

* on the left will be crappified image and the right our original images

* now we initiate UNET here

* Now we need these generated images saved away so we can use them for our critic model

* now lets build our critic

* now we combine the two models together into a gan

* then the last thing we had to define our gan
