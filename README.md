# Deep-Convolutional-Generative-Adversarial-Networs
Implementation of Deep Convolutional GANs in TensorFlow

Implementing the paper [Unsupervised Representationa Learning with Deep Convolutional Generative Adversarial Networks in TensorFlow ](https://arxiv.org/pdf/1511.06434.pdf) using TensorFlow. 
GAN's basically consist of a Generator and a Discriminator. I like to think of the *Generator* as a thief that makes counterfiet bank notes, and the *Discriminator* as a policeman trying to detect the counterfiet currency (an analogy derived from the [original Goodfellow paper on GANs](https://arxiv.org/pdf/1406.2661.pdf)). 

On training, the Generator becomes progressively better at producing images that look real, while the Discriminator gets better at telling them apart. Equilibrium is reached when the Discriminator can no longer discriminate between the real images and those produced by the Generator.

Here, the Generator generates handwritten digits resembling the MNIST dataset

