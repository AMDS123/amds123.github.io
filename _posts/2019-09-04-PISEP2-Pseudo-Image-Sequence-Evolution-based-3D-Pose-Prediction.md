---
layout: post
title: "PISEP^2: Pseudo Image Sequence Evolution based 3D Pose Prediction"
date: 2019-09-04 14:10:49
categories: arXiv_CV
tags: arXiv_CV Inference Prediction Relation
author: Xiaoli Liu, Jianqin Yin, Huaping Liu, Yilong Yin
mathjax: true
---

* content
{:toc}

##### Abstract
Pose prediction is to predict future poses given a window of previous poses. In this paper, we propose a new problem that predicts poses using 3D joint coordinate sequences. Different from the traditional pose prediction based on Mocap frames, this problem is convenient to use in real applications due to its simple sensors to capture data. We also present a new framework, PISEP^2 (Pseudo Image Sequence Evolution based 3D Pose Prediction), to address this new problem. Specifically, a skeletal representation is proposed by transforming the joint coordinate sequence into an image sequence, which can model the different correlations of different joints. With this image based skeletal representation, we model the pose prediction as the evolution of image sequence. Moreover, a novel inference network is proposed to predict all future poses in one step by decoupling the decoders in a non-recursive manner. Compared with the recursive sequence to sequence model, we can improve the computational efficiency and avoid error accumulation significantly. Extensive experiments are carried out on two benchmark datasets (e.g. G3D and FNTU). The proposed method achieves the state-of-the-art performance on both datasets, which demonstrates the effectiveness of our proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01818](http://arxiv.org/abs/1909.01818)

##### PDF
[http://arxiv.org/pdf/1909.01818](http://arxiv.org/pdf/1909.01818)

