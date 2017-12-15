---
layout: post
title: "A regularization-based approach for unsupervised image segmentation"
date: 2016-03-08 20:02:28
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation
author: Aleksandar Dimitriev, Matej Kristan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel unsupervised image segmentation algorithm, which aims to segment an image into several coherent parts. It requires no user input, no supervised learning phase and assumes an unknown number of segments. It achieves this by first over-segmenting the image into several hundred superpixels. These are iteratively joined on the basis of a discriminative classifier trained on color and texture information obtained from each superpixel. The output of the classifier is regularized by a Markov random field that lends more influence to neighbouring superpixels that are more similar. In each iteration, similar superpixels fall under the same label, until only a few coherent regions remain in the image. The algorithm was tested on a standard evaluation data set, where it performs on par with state-of-the-art algorithms in term of precision and greatly outperforms the state of the art by reducing the oversegmentation of the object of interest.

##### Abstract (translated by Google)
我们提出了一种新的无监督图像分割算法，其目的是将图像分割成几个相关的部分。它不需要用户输入，也不需要监督学习阶段，并假定未知数量的段。它通过首先将图像分成几百个超像素来实现这一点。这些是基于从每个超像素获得的颜色和纹理信息进行训练的判别式分类器的基础上迭代地加入的。分类器的输出由马尔可夫随机场规则化，这给随机相邻的超像素带来更多的影响。在每次迭代中，类似的超像素都属于同一个标号，直到图像中只剩下少数相干区域。该算法在标准评估数据集上进行测试，其在精确度方面与最先进的算法相当，并且通过减少感兴趣对象的过度度量而大大超过了现有技术水平。

##### URL
[https://arxiv.org/abs/1603.02649](https://arxiv.org/abs/1603.02649)

##### PDF
[https://arxiv.org/pdf/1603.02649](https://arxiv.org/pdf/1603.02649)

