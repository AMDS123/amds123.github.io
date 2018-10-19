---
layout: post
title: "DeepLens: Shallow Depth Of Field From A Single Image"
date: 2018-10-18 15:14:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Lijun Wang, Xiaohui Shen, Jianming Zhang, Oliver Wang, Zhe Lin, Chih-Yao Hsieh, Sarah Kong, Huchuan Lu
mathjax: true
---

* content
{:toc}

##### Abstract
We aim to generate high resolution shallow depth-of-field (DoF) images from a single all-in-focus image with controllable focal distance and aperture size. To achieve this, we propose a novel neural network model comprised of a depth prediction module, a lens blur module, and a guided upsampling module. All modules are differentiable and are learned from data. To train our depth prediction module, we collect a dataset of 2462 RGB-D images captured by mobile phones with a dual-lens camera, and use existing segmentation datasets to improve border prediction. We further leverage a synthetic dataset with known depth to supervise the lens blur and guided upsampling modules. The effectiveness of our system and training strategies are verified in the experiments. Our method can generate high-quality shallow DoF images at high resolution, and produces significantly fewer artifacts than the baselines and existing solutions for single image shallow DoF synthesis. Compared with the iPhone portrait mode, which is a state-of-the-art shallow DoF solution based on a dual-lens depth camera, our method generates comparable results, while allowing for greater flexibility to choose focal points and aperture size, and is not limited to one capture setup.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.08100](https://arxiv.org/abs/1810.08100)

##### PDF
[https://arxiv.org/pdf/1810.08100](https://arxiv.org/pdf/1810.08100)

