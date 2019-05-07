---
layout: post
title: "RGB-D Salient Object Detection Based on Discriminative Cross-modal Transfer Learning"
date: 2017-05-31 03:51:50
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Transfer_Learning Classification Detection
author: Hao Chen, Y.F. Li, Dan Su
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose to utilize Convolutional Neural Networks to boost the performance of depth-induced salient object detection by capturing the high-level representative features for depth modality. We formulate the depth-induced saliency detection as a CNN-based cross-modal transfer problem to bridge the gap between the "data-hungry" nature of CNNs and the unavailability of sufficient labeled training data in depth modality. In the proposed approach, we leverage the auxiliary data from the source modality effectively by training the RGB saliency detection network to obtain the task-specific pre-understanding layers for the target modality. Meanwhile, we exploit the depth-specific information by pre-training a modality classification network that encourages modal-specific representations during the optimizing course. Thus, it could make the feature representations of the RGB and depth modalities as discriminative as possible. These two modules are pre-trained independently and then stitched to initialize and optimize the eventual depth-induced saliency detection model. Experiments demonstrate the effectiveness of the proposed novel pre-training strategy as well as the significant and consistent improvements of the proposed approach over other state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.00122](https://arxiv.org/abs/1703.00122)

##### PDF
[https://arxiv.org/e-print/1703.00122](https://arxiv.org/e-print/1703.00122)

