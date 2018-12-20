---
layout: post
title: "PnP-AdaNet: Plug-and-Play Adversarial Domain Adaptation Network with a Benchmark at Cross-modality Cardiac Segmentation"
date: 2018-12-19 12:21:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN
author: Qi Dou, Cheng Ouyang, Cheng Chen, Hao Chen, Ben Glocker, Xiahai Zhuang, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks have demonstrated the state-of-the-art performance on various medical image computing tasks. Leveraging images from different modalities for the same analysis task holds clinical benefits. However, the generalization capability of deep models on test data with different distributions remain as a major challenge. In this paper, we propose the PnPAdaNet (plug-and-play adversarial domain adaptation network) for adapting segmentation networks between different modalities of medical images, e.g., MRI and CT. We propose to tackle the significant domain shift by aligning the feature spaces of source and target domains in an unsupervised manner. Specifically, a domain adaptation module flexibly replaces the early encoder layers of the source network, and the higher layers are shared between domains. With adversarial learning, we build two discriminators whose inputs are respectively multi-level features and predicted segmentation masks. We have validated our domain adaptation method on cardiac structure segmentation in unpaired MRI and CT. The experimental results with comprehensive ablation studies demonstrate the excellent efficacy of our proposed PnP-AdaNet. Moreover, we introduce a novel benchmark on the cardiac dataset for the task of unsupervised cross-modality domain adaptation. We will make our code and database publicly available, aiming to promote future studies on this challenging yet important research topic in medical imaging.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07907](http://arxiv.org/abs/1812.07907)

##### PDF
[http://arxiv.org/pdf/1812.07907](http://arxiv.org/pdf/1812.07907)

