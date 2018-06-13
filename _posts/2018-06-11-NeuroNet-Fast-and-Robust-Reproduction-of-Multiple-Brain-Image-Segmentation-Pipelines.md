---
layout: post
title: "NeuroNet: Fast and Robust Reproduction of Multiple Brain Image Segmentation Pipelines"
date: 2018-06-11 20:21:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Martin Rajchl, Nick Pawlowski, Daniel Rueckert, Paul M. Matthews, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
NeuroNet is a deep convolutional neural network mimicking multiple popular and state-of-the-art brain segmentation tools including FSL, SPM, and MALPEM. The network is trained on 5,000 T1-weighted brain MRI scans from the UK Biobank Imaging Study that have been automatically segmented into brain tissue and cortical and sub-cortical structures using the standard neuroimaging pipelines. Training a single model from these complementary and partially overlapping label maps yields a new powerful "all-in-one", multi-output segmentation tool. The processing time for a single subject is reduced by an order of magnitude compared to running each individual software package. We demonstrate very good reproducibility of the original outputs while increasing robustness to variations in the input data. We believe NeuroNet could be an important tool in large-scale population imaging studies and serve as a new standard in neuroscience by reducing the risk of introducing bias when choosing a specific software package.

##### Abstract (translated by Google)
NeuroNet是一个深度卷积神经网络，模仿多种流行的和最先进的大脑分割工具，包括FSL，SPM和MALPEM。该网络接受来自英国生物银行影像学研究的5,000次T1加权脑MRI扫描的训练，该扫描已使用标准神经影像管道自动分割为脑组织和皮层以及亚皮层结构。从这些互补和部分重叠的标签地图中训练单一模型会产生新的强大的“一体化”多输出分割工具。与运行每个软件包相比，单个主题的处理时间减少了一个数量级。我们展示了原始输出的非常好的重现性，同时增加了对输入数据变化的鲁棒性。我们相信NeuroNet可能成为大规模人群影像学研究的重要工具，并通过降低选择特定软件包时引入偏倚的风险，成为神经科学的新标准。

##### URL
[http://arxiv.org/abs/1806.04224](http://arxiv.org/abs/1806.04224)

##### PDF
[http://arxiv.org/pdf/1806.04224](http://arxiv.org/pdf/1806.04224)

