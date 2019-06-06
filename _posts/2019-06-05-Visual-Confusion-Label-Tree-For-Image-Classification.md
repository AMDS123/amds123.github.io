---
layout: post
title: "Visual Confusion Label Tree For Image Classification"
date: 2019-06-05 13:06:11
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Yuntao Liu, Yong Dou, Ruochun Jin, Rongchun Li
mathjax: true
---

* content
{:toc}

##### Abstract
Convolution neural network models are widely used in image classification tasks. However, the running time of such models is so long that it is not the conforming to the strict real-time requirement of mobile devices. In order to optimize models and meet the requirement mentioned above, we propose a method that replaces the fully-connected layers of convolution neural network models with a tree classifier. Specifically, we construct a Visual Confusion Label Tree based on the output of the convolution neural network models, and use a multi-kernel SVM plus classifier with hierarchical constraints to train the tree classifier. Focusing on those confusion subsets instead of the entire set of categories makes the tree classifier more discriminative and the replacement of the fully-connected layers reduces the original running time. Experiments show that our tree classifier obtains a significant improvement over the state-of-the-art tree classifier by 4.3% and 2.4% in terms of top-1 accuracy on CIFAR-100 and ImageNet datasets respectively. Additionally, our method achieves 124x and 115x speedup ratio compared with fully-connected layers on AlexNet and VGG16 without accuracy decline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02012](http://arxiv.org/abs/1906.02012)

##### PDF
[http://arxiv.org/pdf/1906.02012](http://arxiv.org/pdf/1906.02012)

