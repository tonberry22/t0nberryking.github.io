---
title: "Generative Adversarial Network for design generation"
excerpt: "Training a Generative Adversarial Network to learn and generate pictures and designs of your choice"
header:
  image: /assets/images/DCGAN256/clothes-image-1.gif
  teaser: /assets/images/DCGAN256/clothes-image-1.gif
gallery:
  - url: /assets/images/DCGAN256/clothes-image-2.png
    image_path: assets/images/DCGAN256/clothes-image-2.png
    alt: "teaser image 1"
  - url: /assets/images/DCGAN256/shoes-image-1.png
    image_path: assets/images/DCGAN256/shoes-image-1.png
    alt: "teaser image 2"
  - url: /assets/images/DCGAN256/shoes-image-2.png
    image_path: assets/images/DCGAN256/shoes-image-2.png
    alt: "teaser image 3"
---

A generative adversarial network (GAN) pits two neural networks in a contest against each other in a 'zero-sum game', where one network is the 'classifier' and the other one tries to fool this classifier by generating data as a 'generator'.

Given a training set, the generator learns to generate data similar to that set. This data could be normal data or also photographs. The classifier or discriminator also updates itself with each session, and the two networks work together in an unsupervised learning manner, akin to an evolutionary arms race in biology.


{% include gallery caption="Sample outputs of the GAN" %}

<a href="https://github.com/tonberry22/DCGAN256" target="_blank">Click here to see the github repository and run it yourself!</a>