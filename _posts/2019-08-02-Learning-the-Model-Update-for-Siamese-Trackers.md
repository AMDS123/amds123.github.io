---
layout: post
title: "Learning the Model Update for Siamese Trackers"
date: 2019-08-02 13:40:43
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Lichao Zhang, Abel Gonzalez-Garcia, Joost van de Weijer, Martin Danelljan, Fahad Shahbaz Khan
mathjax: true
---

* content
{:toc}

##### Abstract
Siamese approaches address the visual tracking problem by extracting an appearance template from the current frame, which is used to localize the target in the next frame. In general, this template is linearly combined with the accumulated template from the previous frame, resulting in an exponential decay of information over time. While such an approach to updating has led to improved results, its simplicity limits the potential gain likely to be obtained by learning to update. Therefore, we propose to replace the handcrafted update function with a method which learns to update. We use a convolutional neural network, called UpdateNet, which given the initial template, the accumulated template and the template of the current frame aims to estimate the optimal template for the next frame. The UpdateNet is compact and can easily be integrated into existing Siamese trackers. We demonstrate the generality of the proposed approach by applying it to two Siamese trackers, SiamFC and DaSiamRPN. Extensive experiments on VOT2016, VOT2018, LaSOT, and TrackingNet datasets demonstrate that our UpdateNet effectively predicts the new target template, outperforming the standard linear update. On the large-scale TrackingNet dataset, our UpdateNet improves the results of DaSiamRPN with an absolute gain of 3.9% in terms of success score.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00855](http://arxiv.org/abs/1908.00855)

##### PDF
[http://arxiv.org/pdf/1908.00855](http://arxiv.org/pdf/1908.00855)

