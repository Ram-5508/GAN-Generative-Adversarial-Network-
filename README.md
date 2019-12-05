# GAN-Generative-Adversarial-Network-

This neural net creates a new image based on the training data. It contains two parts: Generator and discriminator.

The Discriminator is trained with the real images and it predicts whether a image is real or fake based on the trained model.

The Generator generates a new image and is labelled real image. Then the generated image is sent into the discriminatr. The discriminator calculates the loss between the real image and generated image and sends the loss to the generator.The generator tries to reduce the loss value of discriminator and tries to fools the discriminator to beleive the generated image is real image
