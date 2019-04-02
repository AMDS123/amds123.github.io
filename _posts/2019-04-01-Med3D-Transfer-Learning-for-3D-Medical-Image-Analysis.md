---
layout: post
title: "Med3D: Transfer Learning for 3D Medical Image Analysis"
date: 2019-04-01 08:14:29
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Transfer_Learning Classification Deep_Learning
author: Sihong Chen, Kai Ma, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
The performance on deep learning is significantly affected by volume of training data. Models pre-trained from massive dataset such as ImageNet become a powerful weapon for speeding up training convergence and improving accuracy. Similarly, models based on large dataset are important for the development of deep learning in 3D medical images. However, it is extremely challenging to build a sufficiently large dataset due to difficulty of data acquisition and annotation in 3D medical imaging. We aggregate the dataset from several medical challenges to build 3DSeg-8 dataset with diverse modalities, target organs, and pathologies. To extract general medical three-dimension (3D) features, we design a heterogeneous 3D network called Med3D to co-train multi-domain 3DSeg-8 so as to make a series of pre-trained models. We transfer Med3D pre-trained models to lung segmentation in LIDC dataset, pulmonary nodule classification in LIDC dataset and liver segmentation on LiTS challenge. Experiments show that the Med3D can accelerate the training convergence speed of target 3D medical tasks 2 times compared with model pre-trained on Kinetics dataset, and 10 times compared with training from scratch as well as improve accuracy ranging from 3\% to 20\%. Transferring our Med3D model on state-the-of-art DenseASPP segmentation network, in case of single model, we achieve 94.6\% Dice coefficient which approaches the result of top-ranged algorithms on the LiTS challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00625](http://arxiv.org/abs/1904.00625)

##### PDF
[http://arxiv.org/pdf/1904.00625](http://arxiv.org/pdf/1904.00625)

