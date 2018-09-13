---
layout: post
title: "JigsawNet: Shredded Image Reassembly using Convolutional Neural Network and Loop-based Composition"
date: 2018-09-11 20:07:27
categories: arXiv_CV
tags: arXiv_CV CNN
author: Canyu Le, Xin Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel algorithm to reassemble an arbitrarily shredded image to its original status. Existing reassembly pipelines commonly consist of a local matching stage and a global compositions stage. In the local stage, a key challenge in fragment reassembly is to reliably compute and identify correct pairwise matching, for which most existing algorithms use handcrafted features, and hence, cannot reliably handle complicated puzzles. We build a deep convolutional neural network to detect the compatibility of a pairwise stitching, and use it to prune computed pairwise matches. To improve the network efficiency and accuracy, we transfer the calculation of CNN to the stitching region and apply a boost training strategy. In the global composition stage, we modify the commonly adopted greedy edge selection strategies to two new loop closure based searching algorithms. Extensive experiments show that our algorithm significantly outperforms existing methods on solving various puzzles, especially those challenging ones with many fragment pieces.

##### Abstract (translated by Google)
本文提出了一种新的算法，将任意切碎的图像重新组合到其原始状态。现有的重组管道通常包括局部匹配阶段和全局组合阶段。在本地阶段，片段重组的一个关键挑战是可靠地计算和识别正确的成对匹配，大多数现有算法使用手工制作的特征，因此无法可靠地处理复杂的谜题。我们构建了一个深度卷积神经网络来检测成对拼接的兼容性，并用它来修剪计算的成对匹配。为了提高网络效率和准确性，我们将CNN的计算转移到拼接区域并应用加速训练策略。在全局组合阶段，我们将通常采用的贪婪边缘选择策略修改为两个基于循环闭合的搜索算法。大量实验表明，我们的算法在解决各种难题方面明显优于现有方法，特别是那些具有许多碎片的挑战性难题。

##### URL
[http://arxiv.org/abs/1809.04137](http://arxiv.org/abs/1809.04137)

##### PDF
[http://arxiv.org/pdf/1809.04137](http://arxiv.org/pdf/1809.04137)

