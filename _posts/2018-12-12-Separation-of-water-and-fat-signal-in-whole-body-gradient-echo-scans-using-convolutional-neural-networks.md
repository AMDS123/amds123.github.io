---
layout: post
title: "Separation of water and fat signal in whole-body gradient echo scans using convolutional neural networks"
date: 2018-12-12 12:51:12
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Jonathan Andersson (1), H&#xe5;kan Ahlstr&#xf6;m (1 and 2), Joel Kullberg (1 and 2) ((1) Section of Radiology, Department of Surgical Sciences, Uppsala University, Uppsala, Sweden, (2) Antaros Medical, M&#xf6;lndal, Sweden)
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To perform and evaluate water and fat signal separation of whole-body gradient echo scans using convolutional neural networks. 
 Methods: Whole-body gradient echo scans of 240 subjects, each consisting of five bipolar echoes, were used. Reference fat fraction maps were created using a conventional method. Convolutional neural networks, more specifically 2D U-nets, were trained using 5-fold cross-validation with one or several echoes as input, using the squared difference between the output and the reference fat fraction maps as the loss function. The outputs of the networks were assessed by the loss function, measured liver fat fractions, and visually. Training was performed using a GPU. Inference was performed both using the GPU as well as a CPU. 
 Results: The final loss of the validation data decreased when using more echoes as input, and the loss curves indicated convergence. The liver fat fractions could be estimated using only one echo, but results were improved by use of more echoes. Visual assessment found the quality of the outputs of the networks to be similar to the reference even when using only one echo, with slight improvements when using more echoes. Training a network took at most 28.6 h. Inference time of a whole-body scan took at most 3.7 s using the GPU and 5.8 min using the CPU. 
 Conclusion: It is possible to perform water and fat signal separation of whole-body gradient echo scans using convolutional neural networks. Separation was possible using only one echo, although using more echoes improved the results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04922](http://arxiv.org/abs/1812.04922)

##### PDF
[http://arxiv.org/pdf/1812.04922](http://arxiv.org/pdf/1812.04922)

