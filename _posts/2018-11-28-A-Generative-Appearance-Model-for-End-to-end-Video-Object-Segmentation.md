---
layout: post
title: "A Generative Appearance Model for End-to-end Video Object Segmentation"
date: 2018-11-28 15:11:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Joakim Johnander, Martin Danelljan, Emil Brissman, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
One of the fundamental challenges in video object segmentation is to find an effective representation of the target and background appearance. The best performing approaches resort to extensive fine-tuning of a convolutional neural network for this purpose. Besides being prohibitively expensive, this strategy cannot be truly trained end-to-end since the online fine-tuning procedure is not integrated into the offline training of the network. 
 To address these issues, we propose a network architecture that learns a powerful representation of the target and background appearance in a single forward pass. The introduced appearance module learns a probabilistic generative model of target and background feature distributions. Given a new image, it predicts the posterior class probabilities, providing a highly discriminative cue, which is processed in later network modules. Both the learning and prediction stages of our appearance module are fully differentiable, enabling true end-to-end training of the entire segmentation pipeline. Comprehensive experiments demonstrate the effectiveness of the proposed approach on three video object segmentation benchmarks. We close the gap to approaches based on online fine-tuning on DAVIS17, while operating at 15 FPS on a single GPU. Furthermore, our method outperforms all published approaches on the large-scale YouTube-VOS dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11611](http://arxiv.org/abs/1811.11611)

##### PDF
[http://arxiv.org/pdf/1811.11611](http://arxiv.org/pdf/1811.11611)

