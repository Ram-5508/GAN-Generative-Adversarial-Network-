# GAN-Generative-Adversarial-Network-

This neural net creates a new image based on the training data. It contains two parts: Generator and discriminator.

The Discriminator is trained with the real images and it predicts whether a image is real or fake based on the trained model.

The Generator generates a new image and is labelled real image. Then the generated image is sent into the discriminator. The discriminator calculates the loss between the real image and generated image and sends the loss to the generator.The generator tries to reduce the loss value of discriminator and tries to fools the discriminator to beleive that the generated image is real image.

Here I have used mnist dataset. I have taken 500 images of number 9 and trained the model with 500 epochs. The generated image looks like 9 but its not accurate. I dont have a GPU. So it took around half an hour to train the model. It's always better to run these model with GPU.

The image GAN_1 was trained with 200 epochs and the image GAN_2 was trained with 500 epochs.

