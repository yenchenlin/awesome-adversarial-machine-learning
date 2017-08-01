
# Awesome Adversarial Machine Learning: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome adversarial machine learning resources, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Table of Contents

 - [Blogs](#blogs)
 - [Papers](#papers)
 - [Talks](#talks)

## Blogs
 * [Breaking Linear Classifiers on ImageNet](http://karpathy.github.io/2015/03/30/breaking-convnets/), A. Karpathy et al.
 * [Breaking things is easy](http://www.cleverhans.io/security/privacy/ml/2016/12/16/breaking-things-is-easy.html), N. Papernot & I. Goodfellow et al.
 * [Attacking Machine Learning with Adversarial Examples](https://blog.openai.com/adversarial-example-research/), N. Papernot, I. Goodfellow, S. Huang, Y. Duan, P. Abbeel, J. Clark.
 * [Introduction to Adversarial Machine Learning](https://mascherari.press/introduction-to-adversarial-machine-learning/), Sarah Jamie Lewis.
 * [Robust Adversarial Examples](https://blog.openai.com/robust-adversarial-inputs/), Anish Athalye.
 
## Papers
### General
 * [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199), C. Szegedy et al., arxiv 2014
 * [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572), I. Goodfellow et al., ICLR 2015

### Attack
**Image Classification**

 * [DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599), S. Moosavi-Dezfooli et al., CVPR 2016
 * [The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528), N. Papernot et al., ESSP 2016
 * [Transferability in Machine Learning: from Phenomena to Black-Box Attacks using Adversarial Samples](https://arxiv.org/abs/1605.07277), N. Papernot et al., arxiv 2016
 * [Adversarial Examples In The Physical World](https://arxiv.org/pdf/1607.02533v3.pdf), A. Kurakin et al., ICLR workshop 2017 
 * [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770) Liu et al., ICLR 2017
 * [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644) N. Carlini et al., SSP 2017
 * [Practical Black-Box Attacks against Deep Learning Systems using Adversarial Examples](https://arxiv.org/abs/1602.02697), N. Papernot et al., Asia CCS 2017

**Reinforcement Learning**

* [Adversarial attacks on neural network policies](https://arxiv.org/abs/1702.02284), S. Huang et al, ICLR workshop 2017
* [Tactics of Adversarial Attacks on Deep Reinforcement Learning Agents](https://arxiv.org/abs/1703.06748), Y. Lin et al, IJCAI 2017
* [Delving into adversarial attacks on deep policies](https://arxiv.org/abs/1705.06452), J. Kos et al., ICLR workshop 2017

**Segmentation & Object Detection**

* [Adversarial Examples for Semantic Segmentation and Object Detection](https://arxiv.org/pdf/1703.08603.pdf), C. Xie, ICCV 2017

**VAE-GAN**

* [Adversarial examples for generative models](https://arxiv.org/abs/1702.06832), J. Kos et al. arxiv 2017

### Defence

**Adversarial Training**

* [Adversarial Machine Learning At Scale](https://arxiv.org/pdf/1611.01236.pdf), A. Kurakin et al., ICLR 2017
* [Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204), F. Tramèr et al., arxiv 2017

**Defensive Distillation**
* [Distillation as a Defense to Adversarial Perturbations against Deep Neural Networks](https://arxiv.org/pdf/1511.04508.pdf), N. Papernot et al., SSP 2016
* [Extending Defensive Distillation](https://arxiv.org/abs/1705.05264), N. Papernot et al., arxiv 2017

### Regularization
 * [Distributional Smoothing with Virtual Adversarial Training](https://arxiv.org/abs/1507.00677), T. Miyato et al., ICLR 2016
 * [Adversarial Training Methods for Semi-Supervised Text Classification](https://arxiv.org/abs/1605.07725), T. Miyato et al., ICLR 2017

### Others
 * [Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images](https://arxiv.org/abs/1412.1897), A. Nguyen et al., CVPR 2015
 
## Talks
 * [Do Statistical Models Understand the World?](https://www.youtube.com/watch?v=Pq4A2mPCB0Y), I. Goodfellow, 2015
 * [Classifiers under Attack](https://www.usenix.org/conference/enigma2017/conference-program/presentation/evans), David Evans, 2017
  * [Adversarial Examples in Machine Learning](https://www.usenix.org/conference/enigma2017/conference-program/presentation/papernot), Nicolas Papernot, 2017
  * [Poisoning Behavioral Malware Clustering](http://pralab.diee.unica.it/en/node/1121), Biggio. B, Rieck. K, Ariu. D, Wressnegger. C, Corona. I. Giacinto, G. Roli. F, 2014
  * [Is Data Clustering in Adversarial Settings Secure?](http://pralab.diee.unica.it/en/node/955), BBiggio. B, Pillai. I, Rota Bulò. S, Ariu. D, Pelillo. M, Roli. F, 2015
  * [Poisoning complete-linkage hierarchical clustering](http://pralab.diee.unica.it/en/node/1089), Biggio. B, Rota Bulò. S, Pillai. I, Mura. M, Zemene Mequanint. E, Pelillo. M, Roli. F, 2014
  * [Is Feature Selection Secure against Training Data Poisoning?](https://pralab.diee.unica.it/en/node/1191), Xiao. H, Biggio. B, Brown. G, Fumera. G, Eckert. C, Roli. F, 2015
  * [Adversarial Feature Selection Against Evasion Attacks](https://pralab.diee.unica.it/en/node/1188), 	Zhang. F, Chan. PPK, Biggio. B, Yeung. DS, Roli. F, 2016

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yen-Chen Lin](http://yclin.me/) has waived all copyright and related or neighboring rights to this work.
