---
layout: post
title: "Single-frame Regularization for Temporally Stable CNNs"
date: 2019-02-27 10:01:49
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference Relation
author: Gabriel Eilertsen, Rafa&#x142; K. Mantiuk, Jonas Unger
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) can model complicated non-linear relations between images. However, they are notoriously sensitive to small changes in the input. Most CNNs trained to describe image-to-image mappings generate temporally unstable results when applied to video sequences, leading to flickering artifacts and other inconsistencies over time. In order to use CNNs for video material, previous methods have relied on estimating dense frame-to-frame motion information (optical flow) in the training and/or the inference phase, or by exploring recurrent learning structures. We take a different approach to the problem, posing temporal stability as a regularization of the cost function. The regularization is formulated to account for different types of motion that can occur between frames, so that temporally stable CNNs can be trained without the need for video material or expensive motion estimation. The training can be performed as a fine-tuning operation, without architectural modifications of the CNN. Our evaluation shows that the training strategy leads to large improvements in temporal smoothness. Moreover, in situations where the quantity of training data is limited, the regularization can help in boosting the generalization performance to a much larger extent than what is possible with na\"ive augmentation strategies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10424](http://arxiv.org/abs/1902.10424)

##### PDF
[http://arxiv.org/pdf/1902.10424](http://arxiv.org/pdf/1902.10424)

