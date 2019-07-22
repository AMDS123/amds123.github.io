---
layout: post
title: "GestureGAN for Hand Gesture-to-Gesture Translation in the Wild"
date: 2019-07-19 11:01:02
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hao Tang, Wei Wang, Dan Xu, Yan Yan, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Hand gesture-to-gesture translation in the wild is a challenging task since hand gestures can have arbitrary poses, sizes, locations and self-occlusions. Therefore, this task requires a high-level understanding of the mapping between the input source gesture and the output target gesture. To tackle this problem, we propose a novel hand Gesture Generative Adversarial Network (GestureGAN). GestureGAN consists of a single generator $G$ and a discriminator $D$, which takes as input a conditional hand image and a target hand skeleton image. GestureGAN utilizes the hand skeleton information explicitly, and learns the gesture-to-gesture mapping through two novel losses, the color loss and the cycle-consistency loss. The proposed color loss handles the issue of "channel pollution" while back-propagating the gradients. In addition, we present the Fr\'echet ResNet Distance (FRD) to evaluate the quality of generated images. Extensive experiments on two widely used benchmark datasets demonstrate that the proposed GestureGAN achieves state-of-the-art performance on the unconstrained hand gesture-to-gesture translation task. Meanwhile, the generated images are in high-quality and are photo-realistic, allowing them to be used as data augmentation to improve the performance of a hand gesture classifier. Our model and code are available at https://github.com/Ha0Tang/GestureGAN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.04859](http://arxiv.org/abs/1808.04859)

##### PDF
[http://arxiv.org/pdf/1808.04859](http://arxiv.org/pdf/1808.04859)

