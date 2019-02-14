---
layout: post
title: "SECTOR: A Neural Model for Coherent Topic Segmentation and Classification"
date: 2019-02-13 09:00:16
categories: arXiv_CL
tags: arXiv_CL Salient Segmentation Embedding RNN Classification
author: Sebastian Arnold, Rudolf Schneider, Philippe Cudr&#xe9;-Mauroux, Felix A. Gers, Alexander L&#xf6;ser
mathjax: true
---

* content
{:toc}

##### Abstract
When searching for information, a human reader first glances over a document, spots relevant sections and then focuses on a few sentences for resolving her intention. However, the high variance of document structure complicates to identify the salient topic of a given section at a glance. To tackle this challenge, we present SECTOR, a model to support machine reading systems by segmenting documents into coherent sections and assigning topic labels to each section. Our deep neural network architecture learns a latent topic embedding over the course of a document. This can be leveraged to classify local topics from plain text and segment a document at topic shifts. In addition, we contribute WikiSection, a publicly available dataset with 242k labeled sections in English and German from two distinct domains: diseases and cities. From our extensive evaluation of 20 architectures, we report a highest score of 71.6% F1 for the segmentation and classification of 30 topics from the English city domain, scored by our SECTOR LSTM model with bloom filter embeddings and bidirectional segmentation. This is a significant improvement of 29.5 points F1 compared to state-of-the-art CNN classifiers with baseline segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04793](http://arxiv.org/abs/1902.04793)

##### PDF
[http://arxiv.org/pdf/1902.04793](http://arxiv.org/pdf/1902.04793)

