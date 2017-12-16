---
layout: post
title: "Deep Cropping via Attention Box Prediction and Aesthetics Assessment"
date: 2017-10-22 21:03:01
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Deep_Learning Prediction
author: Wenguan Wang, Jianbing Shen
mathjax: true
---

* content
{:toc}

##### Abstract
We model the photo cropping problem as a cascade of attention box regression and aesthetic quality classification, based on deep learning. A neural network is designed that has two branches for predicting attention bounding box and analyzing aesthetics, respectively. The predicted attention box is treated as an initial crop window where a set of cropping candidates are generated around it, without missing important information. Then, aesthetics assessment is employed to select the final crop as the one with the best aesthetic quality. With our network, cropping candidates share features within full-image convolutional feature maps, thus avoiding repeated feature computation and leading to higher computation efficiency. Via leveraging rich data for attention prediction and aesthetics assessment, the proposed method produces high-quality cropping results, even with the limited availability of training data for photo cropping. The experimental results demonstrate the competitive results and fast processing speed (5 fps with all steps).

##### Abstract (translated by Google)
我们将照片裁剪问题建模为基于深度学习的关注框回归和美学质量分类的级联。设计了一个神经网络，该神经网络分别具有两个分支来预测关注边框和分析美学。预测的关注框被视为初始裁剪窗口，在其中生成一组裁剪候选项，而不会丢失重要信息。然后，美学评估被用来选择最后的作物作为最美观的品质。利用我们的网络，裁剪候选者在全图像卷积特征映射中共享特征，从而避免重复的特征计算并且导致更高的计算效率。通过利用丰富的数据进行关注预测和美学评估，所提出的方法即使在照片裁剪的训练数据有限的情况下也能产生高质量的裁剪结果。实验结果证明了竞争结果和快速的处理速度（每步5fps）。

##### URL
[https://arxiv.org/abs/1710.08014](https://arxiv.org/abs/1710.08014)

##### PDF
[https://arxiv.org/pdf/1710.08014](https://arxiv.org/pdf/1710.08014)

