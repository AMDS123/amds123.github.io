---
layout: post
title: "Guided Proofreading of Automatic Segmentations for Connectomics"
date: 2017-04-04 01:46:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Daniel Haehn, Verena Kaynig, James Tompkin, Jeff W. Lichtman, Hanspeter Pfister
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic cell image segmentation methods in connectomics produce merge and split errors, which require correction through proofreading. Previous research has identified the visual search for these errors as the bottleneck in interactive proofreading. To aid error correction, we develop two classifiers that automatically recommend candidate merges and splits to the user. These classifiers use a convolutional neural network (CNN) that has been trained with errors in automatic segmentations against expert-labeled ground truth. Our classifiers detect potentially-erroneous regions by considering a large context region around a segmentation boundary. Corrections can then be performed by a user with yes/no decisions, which reduces variation of information 7.5x faster than previous proofreading methods. We also present a fully-automatic mode that uses a probability threshold to make merge/split decisions. Extensive experiments using the automatic approach and comparing performance of novice and expert users demonstrate that our method performs favorably against state-of-the-art proofreading methods on different connectomics datasets.

##### Abstract (translated by Google)
连接学中的细胞图像自动分割方法会产生合并和分割错误，需要通过校对来纠正。以往的研究已经将这些错误的视觉搜索确定为交互式校对的瓶颈。为了帮助纠错，我们开发了两个分类器，自动向用户推荐候选合并和分割。这些分类器使用卷积神经网络（CNN），该卷积神经网络针对专家标记的基本事实在自动分割中进行了错误训练。我们的分类器通过考虑分割边界周围的大的上下文区域来检测潜在的错误区域。然后可以由用户进行校正，是/否决定，这比以前的校对方法减少了7.5倍的信息变化。我们还提出了一种使用概率阈值进行合并/拆分决策的全自动模式。使用自动方法进行的大量实验以及比较新手和专家用户的性能表明，我们的方法在不同的连接组学数据集上执行最新的校对方法。

##### URL
[https://arxiv.org/abs/1704.00848](https://arxiv.org/abs/1704.00848)

##### PDF
[https://arxiv.org/pdf/1704.00848](https://arxiv.org/pdf/1704.00848)

