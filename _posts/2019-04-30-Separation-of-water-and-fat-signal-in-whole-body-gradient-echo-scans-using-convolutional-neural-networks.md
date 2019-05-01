---
layout: post
title: "Separation of water and fat signal in whole-body gradient echo scans using convolutional neural networks"
date: 2019-04-30 13:08:22
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Jonathan Andersson, H&#xe5;kan Ahlstr&#xf6;m, Joel Kullberg
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To perform and evaluate water-fat signal separation of whole-body gradient echo scans using convolutional neural networks. 
 Methods: Whole-body gradient echo scans of 240 subjects, each consisting of 5 bipolar echoes, were used. Reference fat fraction maps were created using a conventional method. Convolutional neural networks, more specifically 2D U-nets, were trained using 5-fold cross-validation with 1 or several echoes as input, using the squared difference between the output and the reference fat fraction maps as the loss function. The outputs of the networks were assessed by the loss function, measured liver fat fractions, and visually. Training was performed using a graphics processing unit (GPU). Inference was performed using the GPU as well as a central processing unit (CPU). 
 Results: The loss curves indicated convergence, and the final loss of the validation data decreased when using more echoes as input. The liver fat fractions could be estimated using only 1 echo, but results were improved by use of more echoes. Visual assessment found the quality of the outputs of the networks to be similar to the reference even when using only 1 echo, with slight improvements when using more echoes. Training a network took at most 28.6 h. Inference time of a whole-body scan took at most 3.7 s using the GPU and 5.8 min using the CPU. 
 Conclusion: It is possible to perform water-fat signal separation of whole-body gradient echo scans using convolutional neural networks. Separation was possible using only 1 echo, although using more echoes improved the results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04922](http://arxiv.org/abs/1812.04922)

##### PDF
[http://arxiv.org/pdf/1812.04922](http://arxiv.org/pdf/1812.04922)

