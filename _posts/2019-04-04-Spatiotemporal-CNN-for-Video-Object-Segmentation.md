---
layout: post
title: "Spatiotemporal CNN for Video Object Segmentation"
date: 2019-04-04 05:53:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Attention Prediction
author: Kai Xu, Longyin Wen, Guorong Li, Liefeng Bo, Qingming Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a unified, end-to-end trainable spatiotemporal CNN model for VOS, which consists of two branches, i.e., the temporal coherence branch and the spatial segmentation branch. Specifically, the temporal coherence branch pretrained in an adversarial fashion from unlabeled video data, is designed to capture the dynamic appearance and motion cues of video sequences to guide object segmentation. The spatial segmentation branch focuses on segmenting objects accurately based on the learned appearance and motion cues. To obtain accurate segmentation results, we design a coarse-to-fine process to sequentially apply a designed attention module on multi-scale feature maps, and concatenate them to produce the final prediction. In this way, the spatial segmentation branch is enforced to gradually concentrate on object regions. These two branches are jointly fine-tuned on video segmentation sequences in an end-to-end manner. Several experiments are carried out on three challenging datasets (i.e., DAVIS-2016, DAVIS-2017 and Youtube-Object) to show that our method achieves favorable performance against the state-of-the-arts. Code is available at https://github.com/longyin880815/STCNN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02363](http://arxiv.org/abs/1904.02363)

##### PDF
[http://arxiv.org/pdf/1904.02363](http://arxiv.org/pdf/1904.02363)

