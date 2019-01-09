---
layout: post
title: "Interpretable BoW Networks for Adversarial Example Detection"
date: 2019-01-08 10:04:33
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Prediction Detection
author: Krishna Kanth Nakka, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
The standard approach to providing interpretability to deep convolutional neural networks (CNNs) consists of visualizing either their feature maps, or the image regions that contribute the most to the prediction. In this paper, we introduce an alternative strategy to interpret the results of a CNN. To this end, we leverage a Bag of visual Word representation within the network and associate a visual and semantic meaning to the corresponding codebook elements via the use of a generative adversarial network. The reason behind the prediction for a new sample can then be interpreted by looking at the visual representation of the most highly activated codeword. We then propose to exploit our interpretable BoW networks for adversarial example detection. To this end, we build upon the intuition that, while adversarial samples look very similar to real images, to produce incorrect predictions, they should activate codewords with a significantly different visual representation. We therefore cast the adversarial example detection problem as that of comparing the input image with the most highly activated visual codeword. As evidenced by our experiments, this allows us to outperform the state-of-the-art adversarial example detection methods on standard benchmarks, independently of the attack strategy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02229](http://arxiv.org/abs/1901.02229)

##### PDF
[http://arxiv.org/pdf/1901.02229](http://arxiv.org/pdf/1901.02229)

