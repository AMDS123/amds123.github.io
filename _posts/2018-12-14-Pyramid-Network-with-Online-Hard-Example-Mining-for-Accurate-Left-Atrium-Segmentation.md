---
layout: post
title: "Pyramid Network with Online Hard Example Mining for Accurate Left Atrium Segmentation"
date: 2018-12-14 07:28:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Prediction
author: Cheng Bian, Xin Yang, Jianqiang Ma, Shen Zheng, Yu-An Liu, Reza Nezafat, Pheng-Ann Heng, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately segmenting left atrium in MR volume can benefit the ablation procedure of atrial fibrillation. Traditional automated solutions often fail in relieving experts from the labor-intensive manual labeling. In this paper, we propose a deep neural network based solution for automated left atrium segmentation in gadolinium-enhanced MR volumes with promising performance. We firstly argue that, for this volumetric segmentation task, networks in 2D fashion can present great superiorities in time efficiency and segmentation accuracy than networks with 3D fashion. Considering the highly varying shape of atrium and the branchy structure of associated pulmonary veins, we propose to adopt a pyramid module to collect semantic cues in feature maps from multiple scales for fine-grained segmentation. Also, to promote our network in classifying the hard examples, we propose an Online Hard Negative Example Mining strategy to identify voxels in slices with low classification certainties and penalize the wrong predictions on them. Finally, we devise a competitive training scheme to further boost the generalization ability of networks. Extensively verified on 20 testing volumes, our proposed framework achieves an average Dice of 92.83% in segmenting the left atria and pulmonary veins.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05802](http://arxiv.org/abs/1812.05802)

##### PDF
[http://arxiv.org/pdf/1812.05802](http://arxiv.org/pdf/1812.05802)

