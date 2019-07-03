---
layout: post
title: "Learning to aggregate feature representations"
date: 2019-07-01 19:35:17
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Guy Gaziv
mathjax: true
---

* content
{:toc}

##### Abstract
The Algonauts challenge require to construct an multi-subject encoder of images to brain activity signals. Deep networks such as ResNet-50 and AlexNet trained for image classification are known to produce feature representations along their intermediate stages which closely mimic the visual hierarchy. However the challenges introduced in the Algonauts project, including combining data from multiple subjects, relying on very few similarity data points, solving for various ROIs, and multi-modality, require devising a flexible framework which can efficiently accommodate that. Here we build upon a recent state-of-the-art classification network (SE-ResNeXt-50) and construct an adaptive combination of its intermediate representations. While the pretrained network serves as a backbone of our model, we \emph{learn} how to aggregate feature representations along five stages of the network. During learning, our construction enables to modulate and screen outputs from each stage along the network as governed by the optimized objective. We applied our method to the Algonauts2019 fMRI and MEG challenges. Using the combined fMRI and MEG data, our approach was rated among the leading five for both challenges. Surprisingly we find that for both the lower and higher order areas (EVC and IT) the adaptive aggregation favors features stemming at later stages of the network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01034](http://arxiv.org/abs/1907.01034)

##### PDF
[http://arxiv.org/pdf/1907.01034](http://arxiv.org/pdf/1907.01034)

