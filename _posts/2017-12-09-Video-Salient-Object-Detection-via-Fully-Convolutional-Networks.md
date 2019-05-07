---
layout: post
title: "Video Salient Object Detection via Fully Convolutional Networks"
date: 2017-12-09 01:42:49
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Inference Deep_Learning Detection
author: Wenguan Wang, Jianbing Shen, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a deep learning model to efficiently detect salient regions in videos. It addresses two important issues: (1) deep video saliency model training with the absence of sufficiently large and pixel-wise annotated video data, and (2) fast video saliency training and detection. The proposed deep video saliency network consists of two modules, for capturing the spatial and temporal saliency information, respectively. The dynamic saliency model, explicitly incorporating saliency estimates from the static saliency model, directly produces spatiotemporal saliency inference without time-consuming optical flow computation. We further propose a novel data augmentation technique that simulates video training data from existing annotated image datasets, which enables our network to learn diverse saliency information and prevents overfitting with the limited number of training videos. Leveraging our synthetic video data (150K video sequences) and real videos, our deep video saliency model successfully learns both spatial and temporal saliency cues, thus producing accurate spatiotemporal saliency estimate. We advance the state-of-the-art on the DAVIS dataset (MAE of .06) and the FBMS dataset (MAE of .07), and do so with much improved speed (2fps with all steps).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.00871](https://arxiv.org/abs/1702.00871)

##### PDF
[https://arxiv.org/pdf/1702.00871](https://arxiv.org/pdf/1702.00871)

