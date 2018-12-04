---
layout: post
title: "Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning"
date: 2018-12-03 03:12:39
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Zhibo Wang, Mengkai Song, Zhifei Zhang, Yang Song, Qian Wang, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Federated learning, i.e., a mobile edge computing framework for deep learning, is a recent advance in privacy-preserving machine learning, where the model is trained in a decentralized manner by the clients, i.e., data curators, preventing the server from directly accessing those private data from the clients. This learning mechanism significantly challenges the attack from the server side. Although the state-of-the-art attacking techniques that incorporated the advance of Generative adversarial networks (GANs) could construct class representatives of the global data distribution among all clients, it is still challenging to distinguishably attack a specific client (i.e., user-level privacy leakage), which is a stronger privacy threat to precisely recover the private data from a specific client. This paper gives the first attempt to explore user-level privacy leakage against the federated learning by the attack from a malicious server. We propose a framework incorporating GAN with a multi-task discriminator, which simultaneously discriminates category, reality, and client identity of input samples. The novel discrimination on client identity enables the generator to recover user specified private data. Unlike existing works that tend to interfere the training process of the federated learning, the proposed method works "invisibly" on the server side. The experimental results demonstrate the effectiveness of the proposed attacking approach and the superior to the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00535](http://arxiv.org/abs/1812.00535)

##### PDF
[http://arxiv.org/pdf/1812.00535](http://arxiv.org/pdf/1812.00535)

