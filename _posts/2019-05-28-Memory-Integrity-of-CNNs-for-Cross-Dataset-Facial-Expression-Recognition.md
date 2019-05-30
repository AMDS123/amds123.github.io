---
layout: post
title: "Memory Integrity of CNNs for Cross-Dataset Facial Expression Recognition"
date: 2019-05-28 20:55:57
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Dylan C. Tannugi, Alceu S. Britto Jr., Alessandro L. Koerich
mathjax: true
---

* content
{:toc}

##### Abstract
Facial expression recognition is a major problem in the domain of artificial intelligence. One of the best ways to solve this problem is the use of convolutional neural networks (CNNs). However, a large amount of data is required to train properly these networks but most of the datasets available for facial expression recognition are relatively small. A common way to circumvent the lack of data is to use CNNs trained on large datasets of different domains and fine-tuning the layers of such networks to the target domain. However, the fine-tuning process does not preserve the memory integrity as CNNs have the tendency to forget patterns they have learned. In this paper, we evaluate different strategies of fine-tuning a CNN with the aim of assessing the memory integrity of such strategies in a cross-dataset scenario. A CNN pre-trained on a source dataset is used as the baseline and four adaptation strategies have been evaluated: fine-tuning its fully connected layers; fine-tuning its last convolutional layer and its fully connected layers; retraining the CNN on a target dataset; and the fusion of the source and target datasets and retraining the CNN. Experimental results on four datasets have shown that the fusion of the source and the target datasets provides the best trade-off between accuracy and memory integrity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12082](http://arxiv.org/abs/1905.12082)

##### PDF
[http://arxiv.org/pdf/1905.12082](http://arxiv.org/pdf/1905.12082)

