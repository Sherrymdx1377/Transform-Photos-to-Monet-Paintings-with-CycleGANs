# Transform-Photos-to-Monet-Paintings-with-CycleGANs
In this guided project, we will teach you to build a style transfer tool that can "translate" photos into Monet-esque paintings using CycleGANs. We will study the architecture of CycleGANs and then we will build it by breaking it down into multiple parts.

# About
 
Generative Adversarial Networks, or GANs for short, are a type of deep-learning generative model. A vanilla GAN's architecture involves two networks: a Generator network for generating new examples and a Discriminator network for classifying examples as real (drawn from the training data) or fake (drawn from the Generator). 

GANs typically work with images.  Depending on how we set the objective function of a GAN, the Generator can be used to generate new images that satisfy certain rules. In this guided project, we will be learning about CycleGANs, a class of GANs that can be used for transferring the style of images of one domain onto images in another domain by enforcing Cycle Consistency Loss. For instance, a CycleGAN can "translate" the photo of a landscape into a Monet-esque painting of that landscape.


 # A Look at the Project Ahead

# After completing this guided project you will be able to:

1. Describe the novelties of CycleGANs compared to traditional GANs.

2. Understand the Cycle Consistency Loss and how it's implemented on images.

3. Build the CycleGAN architecture in Keras.

4. Gain good practices in training deep learning models.

5. Implement a pre-trained CycleGAN for image style transfer tasks.
