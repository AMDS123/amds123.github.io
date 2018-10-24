---
layout: post
title: "Efficient Gender Classification Using a Deep LDA-Pruned Net"
date: 2018-10-23 12:40:11
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation Recognition
author: Qing Tian, Tal Arbel, James J. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-time tasks, such as human-computer interaction, require fast and efficient facial gender classification. Although deep CNN nets have been very effective for a multitude of classification tasks, their high space and time demands make them impractical for personal computers and mobile devices without a powerful GPU. In this paper, we develop a 16-layer, yet lightweight, neural network which boosts efficiency while maintaining high accuracy. Our net is pruned from the VGG-16 model starting from the last convolutional (conv) layer where we find neuron activations are highly uncorrelated given the gender. Through Fisher's Linear Discriminant Analysis (LDA), we show that this high decorrelation makes it safe to discard directly last conv layer neurons with high within-class variance and low between-class variance. Combined with either Support Vector Machines (SVM) or Bayesian classification, the reduced CNNs are capable of achieving comparable (or even higher) accuracies on the LFW and CelebA datasets than the original net with fully connected layers. On LFW, only four Conv5_3 neurons are able to maintain a comparably high recognition accuracy, which results in a reduction of total network size by a factor of 70X with a 11 fold speedup. Comparisons with a state-of-the-art pruning method as well as two smaller nets in terms of accuracy loss and convolutional layers pruning rate are also provided.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1704.06305](http://arxiv.org/abs/1704.06305)

##### PDF
[http://arxiv.org/pdf/1704.06305](http://arxiv.org/pdf/1704.06305)

