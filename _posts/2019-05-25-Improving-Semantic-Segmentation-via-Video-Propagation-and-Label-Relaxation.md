---
layout: post
title: "Improving Semantic Segmentation via Video Propagation and Label Relaxation"
date: 2019-05-25 18:56:34
categories: arXiv_AI
tags: arXiv_AI Segmentation Semantic_Segmentation Prediction
author: Yi Zhu, Karan Sapra, Fitsum A. Reda, Kevin J. Shih, Shawn Newsam, Andrew Tao, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation requires large amounts of pixel-wise annotations to learn accurate models. In this paper, we present a video prediction-based methodology to scale up training sets by synthesizing new training samples in order to improve the accuracy of semantic segmentation networks. We exploit video prediction models' ability to predict future frames in order to also predict future labels. A joint propagation strategy is also proposed to alleviate mis-alignments in synthesized samples. We demonstrate that training segmentation models on datasets augmented by the synthesized samples leads to significant improvements in accuracy. Furthermore, we introduce a novel boundary label relaxation technique that makes training robust to annotation noise and propagation artifacts along object boundaries. Our proposed methods achieve state-of-the-art mIoUs of 83.5% on Cityscapes and 82.9% on CamVid. Our single model, without model ensembles, achieves 72.8% mIoU on the KITTI semantic segmentation test set, which surpasses the winning entry of the ROB challenge 2018. Our code and videos can be found at https://nv-adlr.github.io/publication/2018-Segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01593](http://arxiv.org/abs/1812.01593)

##### PDF
[http://arxiv.org/pdf/1812.01593](http://arxiv.org/pdf/1812.01593)

