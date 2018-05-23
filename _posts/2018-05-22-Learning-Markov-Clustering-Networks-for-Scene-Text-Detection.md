---
layout: post
title: "Learning Markov Clustering Networks for Scene Text Detection"
date: 2018-05-22 02:46:39
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference Detection Relation
author: Zichuan Liu, Guosheng Lin, Sheng Yang, Jiashi Feng, Weisi Lin, Wang Ling Goh
mathjax: true
---

* content
{:toc}

##### Abstract
A novel framework named Markov Clustering Network (MCN) is proposed for fast and robust scene text detection. MCN predicts instance-level bounding boxes by firstly converting an image into a Stochastic Flow Graph (SFG) and then performing Markov Clustering on this graph. Our method can detect text objects with arbitrary size and orientation without prior knowledge of object size. The stochastic flow graph encode objects' local correlation and semantic information. An object is modeled as strongly connected nodes, which allows flexible bottom-up detection for scale-varying and rotated objects. MCN generates bounding boxes without using Non-Maximum Suppression, and it can be fully parallelized on GPUs. The evaluation on public benchmarks shows that our method outperforms the existing methods by a large margin in detecting multioriented text objects. MCN achieves new state-of-art performance on challenging MSRA-TD500 dataset with precision of 0.88, recall of 0.79 and F-score of 0.83. Also, MCN achieves realtime inference with frame rate of 34 FPS, which is $1.5\times$ speedup when compared with the fastest scene text detection algorithm.

##### Abstract (translated by Google)
提出了一种新的框架 - 马尔可夫聚类网络（MCN），用于快速，健壮的场景文本检测。 MCN通过首先将图像转换为随机流图（SFG），然后在该图上执行马尔可夫聚类来预测实例级边界框。我们的方法可以检测具有任意大小和方向的文本对象，而无需预先知道对象大小。随机流程图编码对象的本地相关和语义信息。一个对象被建模为强连接的节点，这允许灵活的自下而上检测尺度变化和旋转的对象。 MCN在不使用非最大抑制的情况下生成边界框，并且可以在GPU上完全并行化。公共基准评估表明，我们的方法在检测多方面的文本对象方面大大优于现有的方法。 MCN在具有挑战性的MSRA-TD500数据集上实现了最新的最新性能，精度为0.88，回忆率为0.79，F值为0.83。另外，MCN实现了34帧/秒帧速率的实时推断，与最快的场景文本检测算法相比，速度提高1.5倍。

##### URL
[https://arxiv.org/abs/1805.08365](https://arxiv.org/abs/1805.08365)

##### PDF
[https://arxiv.org/pdf/1805.08365](https://arxiv.org/pdf/1805.08365)

