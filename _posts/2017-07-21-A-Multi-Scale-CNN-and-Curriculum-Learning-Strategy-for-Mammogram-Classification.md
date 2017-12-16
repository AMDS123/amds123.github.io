---
layout: post
title: "A Multi-Scale CNN and Curriculum Learning Strategy for Mammogram Classification"
date: 2017-07-21 17:16:12
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Detection
author: William Lotter, Greg Sorensen, David Cox
mathjax: true
---

* content
{:toc}

##### Abstract
Screening mammography is an important front-line tool for the early detection of breast cancer, and some 39 million exams are conducted each year in the United States alone. Here, we describe a multi-scale convolutional neural network (CNN) trained with a curriculum learning strategy that achieves high levels of accuracy in classifying mammograms. Specifically, we first train CNN-based patch classifiers on segmentation masks of lesions in mammograms, and then use the learned features to initialize a scanning-based model that renders a decision on the whole image, trained end-to-end on outcome data. We demonstrate that our approach effectively handles the "needle in a haystack" nature of full-image mammogram classification, achieving 0.92 AUROC on the DDSM dataset.

##### Abstract (translated by Google)
筛查乳房X光检查是早期发现乳腺癌的重要前线工具，仅在美国就每年进行约3900万次检查。在这里，我们描述了一个多层次的卷积神经网络（CNN）训练与课程学习策略，实现高水平的准确性分类乳房X线照片。具体来说，我们首先在乳房X线照片上对基于CNN的斑块分类器进行训练，然后使用学习的特征初始化一个基于扫描的模型，对整个图像做出决策，对结果数据进行端到端的训练。我们证明，我们的方法有效地处理全图像乳房X线照片分类的“大海捞针”性质，在DDSM数据集上实现0.92 AUROC。

##### URL
[https://arxiv.org/abs/1707.06978](https://arxiv.org/abs/1707.06978)

##### PDF
[https://arxiv.org/pdf/1707.06978](https://arxiv.org/pdf/1707.06978)

