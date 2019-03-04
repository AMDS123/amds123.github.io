---
layout: post
title: "TamperNN: Efficient Tampering Detection of Deployed Neural Nets"
date: 2019-03-01 14:32:45
categories: arXiv_CV
tags: arXiv_CV Face RNN Prediction Detection
author: Erwan Le Merrer, Gilles Tr&#xe9;dan
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are powering the deployment of embedded devices and Internet of Things. Applications range from personal assistants to critical ones such as self-driving cars. It has been shown recently that models obtained from neural nets can be trojaned ; an attacker can then trigger an arbitrary model behavior facing crafted inputs. This has a critical impact on the security and reliability of those deployed devices. 
 We introduce novel algorithms to detect the tampering with deployed models, classifiers in particular. In the remote interaction setup we consider, the proposed strategy is to identify markers of the model input space that are likely to change class if the model is attacked, allowing a user to detect a possible tampering. This setup makes our proposal compatible with a wide rage of scenarios, such as embedded models, or models exposed through prediction APIs. We experiment those tampering detection algorithms on the canonical MNIST dataset, over three different types of neural nets, and facing five different attacks (trojaning, quantization, fine-tuning, compression and watermarking). We then validate over five large models (VGG16, VGG19, ResNet, MobileNet, DenseNet) with a state of the art dataset (VGGFace2), and report results demonstrating the possibility of an efficient detection of model tampering.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00317](http://arxiv.org/abs/1903.00317)

##### PDF
[http://arxiv.org/pdf/1903.00317](http://arxiv.org/pdf/1903.00317)

