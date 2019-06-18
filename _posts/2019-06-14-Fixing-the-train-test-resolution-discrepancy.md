---
layout: post
title: "Fixing the train-test resolution discrepancy"
date: 2019-06-14 22:27:30
categories: arXiv_AI
tags: arXiv_AI Image_Classification Classification
author: Hugo Touvron, Andrea Vedaldi, Matthijs Douze, Herv&#xe9; J&#xe9;gou
mathjax: true
---

* content
{:toc}

##### Abstract
Data-augmentation is key to the training of neural networks for image classification. This paper first shows that existing augmentations induce a significant discrepancy between the typical size of the objects seen by the classifier at train and test time. We experimentally validate that, for a target test resolution, using a lower train resolution offers better classification at test time. 
 We then propose a simple yet effective and efficient strategy to optimize the classifier performance when the train and test resolutions differ. It involves only a computationally cheap fine-tuning of the network at the test resolution. This enables training strong classifiers using small training images. For instance, we obtain 77.1% top-1 accuracy on ImageNet with a ResNet-50 trained on 128x128 images, and 78% with our multi-resolution classification. Conversely, when training a PNASNet at resolution 331x331 and further optimizing for test resolution 480x480, we obtain a test top-1 accuracy of 83.7% (top-5: 96.8%) (single-crop).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06423](http://arxiv.org/abs/1906.06423)

##### PDF
[http://arxiv.org/pdf/1906.06423](http://arxiv.org/pdf/1906.06423)

