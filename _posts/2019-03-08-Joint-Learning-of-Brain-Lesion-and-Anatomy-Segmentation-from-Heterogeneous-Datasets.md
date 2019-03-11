---
layout: post
title: "Joint Learning of Brain Lesion and Anatomy Segmentation from Heterogeneous Datasets"
date: 2019-03-08 13:49:44
categories: arXiv_AI
tags: arXiv_AI Segmentation CNN Quantitative
author: Nicolas Roulet, Diego Fernandez Slezak, Enzo Ferrante
mathjax: true
---

* content
{:toc}

##### Abstract
Brain lesion and anatomy segmentation in magnetic resonance images are fundamental tasks in neuroimaging research and clinical practice. Given enough training data, convolutional neuronal networks (CNN) proved to outperform all existent techniques in both tasks independently. However, to date, little work has been done regarding simultaneous learning of brain lesion and anatomy segmentation from disjoint datasets. 
 In this work we focus on training a single CNN model to predict brain tissue and lesion segmentations using heterogeneous datasets labeled independently, according to only one of these tasks (a common scenario when using publicly available datasets). We show that label contradiction issues can arise in this case, and propose a novel adaptive cross entropy (ACE) loss function that makes such training possible. We provide quantitative evaluation in two different scenarios, benchmarking the proposed method in comparison with a multi-network approach. Our experiments suggest that ACE loss enables training of single models when standard cross entropy and Dice loss functions tend to fail. Moreover, we show that it is possible to achieve competitive results when comparing with multiple networks trained for independent tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03445](http://arxiv.org/abs/1903.03445)

##### PDF
[http://arxiv.org/pdf/1903.03445](http://arxiv.org/pdf/1903.03445)

