---
layout: post
title: "Semantic Object Parsing with Local-Global Long Short-Term Memory"
date: 2015-11-14 05:42:50
categories: arXiv_CV
tags: arXiv_CV CNN Inference RNN Recognition
author: Xiaodan Liang, Xiaohui Shen, Donglai Xiang, Jiashi Feng, Liang Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic object parsing is a fundamental task for understanding objects in detail in computer vision community, where incorporating multi-level contextual information is critical for achieving such fine-grained pixel-level recognition. Prior methods often leverage the contextual information through post-processing predicted confidence maps. In this work, we propose a novel deep Local-Global Long Short-Term Memory (LG-LSTM) architecture to seamlessly incorporate short-distance and long-distance spatial dependencies into the feature learning over all pixel positions. In each LG-LSTM layer, local guidance from neighboring positions and global guidance from the whole image are imposed on each position to better exploit complex local and global contextual information. Individual LSTMs for distinct spatial dimensions are also utilized to intrinsically capture various spatial layouts of semantic parts in the images, yielding distinct hidden and memory cells of each position for each dimension. In our parsing approach, several LG-LSTM layers are stacked and appended to the intermediate convolutional layers to directly enhance visual features, allowing network parameters to be learned in an end-to-end way. The long chains of sequential computation by stacked LG-LSTM layers also enable each pixel to sense a much larger region for inference benefiting from the memorization of previous dependencies in all positions along all dimensions. Comprehensive evaluations on three public datasets well demonstrate the significant superiority of our LG-LSTM over other state-of-the-art methods.

##### Abstract (translated by Google)
语义对象分析是计算机视觉社区中详细理解对象的基本任务，其中结合多级上下文信息对于实现这样的细粒度像素级识别是至关重要的。先前的方法经常通过后处理预测的置信度图来利用上下文信息。在这项工作中，我们提出了一种新颖的深局域全局长短期记忆（LG-LSTM）架构，将短距离和长距离的空间依赖无缝地结合到所有像素位置的特征学习中。在每个LG-LSTM层中，来自相邻位置的本地指导和来自整个图像的全局指导被施加到每个位置以更好地利用复杂的局部和全局情境信息。独立的空间维度的LSTM也被用来内在地捕捉图像中语义部分的各种空间布局，为每个维度产生每个位置的不同的隐藏和记忆单元。在我们的解析方法中，多个LG-LSTM层被堆叠并附加到中间卷积层以直接增强视觉特征，允许以端到端的方式学习网络参数。通过堆叠的LG-LSTM层的连续计算的长链也使每个像素能够感知更大的区域，以便得益于沿着所有维度的所有位置中先前相关性的记忆。对三个公共数据集的综合评估充分证明了我们的LG-LSTM优于其他最先进的方法的显着优势。

##### URL
[https://arxiv.org/abs/1511.04510](https://arxiv.org/abs/1511.04510)

##### PDF
[https://arxiv.org/pdf/1511.04510](https://arxiv.org/pdf/1511.04510)

