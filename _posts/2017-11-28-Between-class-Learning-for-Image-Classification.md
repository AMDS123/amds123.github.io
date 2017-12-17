---
layout: post
title: "Between-class Learning for Image Classification"
date: 2017-11-28 13:31:14
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Yuji Tokozume, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel learning method for image classification called Between-Class learning (BC learning). We generate between-class images by mixing two images belonging to different classes with a random ratio. We then input the mixed image to the model and train the model to output the mixing ratio. BC learning has the ability to impose a constraint on the shape of the feature distributions, and thus the generalization ability is improved. BC learning is originally a method developed for sounds, which can be digitally mixed. Mixing two image data does not appear to make sense; however, we argue that because convolutional neural networks have an aspect of treating input data as waveforms, what works on sounds must also work on images. First, we propose a simple mixing method using internal divisions, which surprisingly proves to significantly improve performance. Second, we propose a mixing method that treats the images as waveforms, which leads to a further improvement in performance. As a result, we achieved 19.4% and 2.26% top-1 errors on ImageNet-1K and CIFAR-10, respectively.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的图像分类学习方法，称为课间学习（BC学习）。我们通过以随机比率混合属于不同类别的两幅图像来生成类间图像。然后我们将混合图像输入到模型中，并训练模型输出混合比率。 BC学习能够对特征分布的形状施加约束，从而提高泛化能力。不列颠哥伦比亚省学习本来是一种为声音开发的方法，可以数字混合使用。混合两个图像数据似乎没有意义;然而，我们认为，因为卷积神经网络将输入数据看作波形的一个方面，所以对声音起作用的东西也必须对图像起作用。首先，我们提出了一种简单的使用内部分割的混合方法，令人惊讶地证明可以显着提高性能。其次，我们提出一种混合方法，将图像作为波形进行处理，从而进一步提高性能。结果，我们分别在ImageNet-1K和CIFAR-10上分别达到了19.4％和2.26％的头号错误。

##### URL
[https://arxiv.org/abs/1711.10284](https://arxiv.org/abs/1711.10284)

##### PDF
[https://arxiv.org/pdf/1711.10284](https://arxiv.org/pdf/1711.10284)

