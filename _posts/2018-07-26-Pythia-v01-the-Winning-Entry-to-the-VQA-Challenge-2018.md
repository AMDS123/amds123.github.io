---
layout: post
title: "Pythia v0.1: the Winning Entry to the VQA Challenge 2018"
date: 2018-07-26 04:57:43
categories: arXiv_CV
tags: arXiv_CV QA Face VQA
author: Yu Jiang, Vivek Natarajan, Xinlei Chen, Marcus Rohrbach, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
This document describes Pythia v0.1, the winning entry from Facebook AI Research (FAIR)'s A-STAR team to the VQA Challenge 2018. 
 Our starting point is a modular re-implementation of the bottom-up top-down (up-down) model. We demonstrate that by making subtle but important changes to the model architecture and the learning rate schedule, fine-tuning image features, and adding data augmentation, we can significantly improve the performance of the up-down model on VQA v2.0 dataset -- from 65.67% to 70.22%. 
 Furthermore, by using a diverse ensemble of models trained with different features and on different datasets, we are able to significantly improve over the 'standard' way of ensembling (i.e. same model with different random seeds) by 1.31%. Overall, we achieve 72.27% on the test-std split of the VQA v2.0 dataset. Our code in its entirety (training, evaluation, data-augmentation, ensembling) and pre-trained models are publicly available at: https://github.com/facebookresearch/pythia.

##### Abstract (translated by Google)
本文档描述了Pythia v0.1，这是Facebook AI Research（FAIR）的A-STAR团队参加VQA挑战赛2018的获奖作品。
 我们的出发点是自上而下自上而下（上下）模型的模块化重新实现。我们通过对模型体系结构和学习速率计划进行微妙但重要的更改，微调图像功能以及添加数据增强来证明，我们可以显着提高VQA v2.0数据集上的上下模型的性能 - 从65.67％到70.22％。
 此外，通过使用由不同特征和不同数据集训练的多样化模型集合，我们能够显着改进“标准”集合方式（即具有不同随机种子的相同模型）1.31％。总体而言，我们在VQA v2.0数据集的test-std拆分中达到了72.27％。我们的代码（培训，评估，数据增强，整合）和预训练模型可在以下网址公开获取：https：//github.com/facebookresearch/pythia。

##### URL
[http://arxiv.org/abs/1807.09956](http://arxiv.org/abs/1807.09956)

##### PDF
[http://arxiv.org/pdf/1807.09956](http://arxiv.org/pdf/1807.09956)

