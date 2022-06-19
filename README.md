# Using GANs to generate synthetic data


Generative adversarial networks (GANs) are algorithmic architectures that use two neural networks, pitting one against the other (thus the “adversarial”) in order to generate new, synthetic instances of data that can pass for real data. They are used widely in image generation, video generation and voice generation.

GANs could be understood more clearly by understanding the underlying differnce between discriminative and generative algorithms.

Discriminative algorithms try to classify input data; that is, given the features of an instance of data, they predict a label or category to which that data belongs.So discriminative algorithms map features to labels. 

They are concerned solely with that correlation. One way to think about generative algorithms is that they do the opposite. Instead of predicting a label given certain features, they attempt to predict features given a certain label.

In a gist:
 1.  Discriminative models learn the boundary between classes.
 2.  Generative models model the distribution of individual classes.

The way GAN works is:

  One neural network, called the generator, generates new data instances, while the other, the discriminator, evaluates them for authenticity; i.e. the     discriminator decides whether each instance of data that it reviews belongs to the actual training dataset or not.
  
