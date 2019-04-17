---
layout: post
title: "Rob-GAN: Generator, Discriminator, and Adversarial Attacker"
date: 2019-04-15 21:12:02
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Deep_Learning
author: Xuanqing Liu, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
We study two important concepts in adversarial deep learning---adversarial training and generative adversarial network (GAN). Adversarial training is the technique used to improve the robustness of discriminator by combining adversarial attacker and discriminator in the training phase. GAN is commonly used for image generation by jointly optimizing discriminator and generator. We show these two concepts are indeed closely related and can be used to strengthen each other---adding a generator to the adversarial training procedure can improve the robustness of discriminators, and adding an adversarial attack to GAN training can improve the convergence speed and lead to better generators. Combining these two insights, we develop a framework called Rob-GAN to jointly optimize generator and discriminator in the presence of adversarial attacks---the generator generates fake images to fool discriminator; the adversarial attacker perturbs real images to fool the discriminator, and the discriminator wants to minimize loss under fake and adversarial images. Through this end-to-end training procedure, we are able to simultaneously improve the convergence speed of GAN training, the quality of synthetic images, and the robustness of discriminator under strong adversarial attacks. Experimental results demonstrate that the obtained classifier is more robust than the state-of-the-art adversarial training approach, and the generator outperforms SN-GAN on ImageNet-143.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.10454](http://arxiv.org/abs/1807.10454)

##### PDF
[http://arxiv.org/pdf/1807.10454](http://arxiv.org/pdf/1807.10454)

