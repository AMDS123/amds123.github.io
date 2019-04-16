---
layout: post
title: "Pythia v0.1: the Winning Entry to the VQA Challenge 2018"
date: 2018-07-27 17:31:54
categories: arXiv_CV
tags: arXiv_CV QA Face VQA
author: Yu Jiang, Vivek Natarajan, Xinlei Chen, Marcus Rohrbach, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
This document describes Pythia v0.1, the winning entry from Facebook AI Research (FAIR)'s A-STAR team to the VQA Challenge 2018. Our starting point is a modular re-implementation of the bottom-up top-down (up-down) model. We demonstrate that by making subtle but important changes to the model architecture and the learning rate schedule, fine-tuning image features, and adding data augmentation, we can significantly improve the performance of the up-down model on VQA v2.0 dataset -- from 65.67% to 70.22%. Furthermore, by using a diverse ensemble of models trained with different features and on different datasets, we are able to significantly improve over the 'standard' way of ensembling (i.e. same model with different random seeds) by 1.31%. Overall, we achieve 72.27% on the test-std split of the VQA v2.0 dataset. Our code in its entirety (training, evaluation, data-augmentation, ensembling) and pre-trained models are publicly available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.09956](https://arxiv.org/abs/1807.09956)

##### PDF
[https://arxiv.org/pdf/1807.09956](https://arxiv.org/pdf/1807.09956)

