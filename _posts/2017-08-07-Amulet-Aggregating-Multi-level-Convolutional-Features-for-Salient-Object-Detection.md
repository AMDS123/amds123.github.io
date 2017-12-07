---
layout: post
title: "Amulet: Aggregating Multi-level Convolutional Features for Salient Object Detection"
date: 2017-08-07 06:29:38
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Inference Detection
author: Pingping Zhang, Dong Wang, Huchuan Lu, Hongyu Wang, Xiang Ruan
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional neural networks (FCNs) have shown outstanding performance in many dense labeling problems. One key pillar of these successes is mining relevant information from features in convolutional layers. However, how to better aggregate multi-level convolutional feature maps for salient object detection is underexplored. In this work, we present Amulet, a generic aggregating multi-level convolutional feature framework for salient object detection. Our framework first integrates multi-level feature maps into multiple resolutions, which simultaneously incorporate coarse semantics and fine details. Then it adaptively learns to combine these feature maps at each resolution and predict saliency maps with the combined features. Finally, the predicted results are efficiently fused to generate the final saliency map. In addition, to achieve accurate boundary inference and semantic enhancement, edge-aware feature maps in low-level layers and the predicted results of low resolution features are recursively embedded into the learning framework. By aggregating multi-level convolutional features in this efficient and flexible manner, the proposed saliency model provides accurate salient object labeling. Comprehensive experiments demonstrate that our method performs favorably against state-of-the art approaches in terms of near all compared evaluation metrics.

##### Abstract (translated by Google)
完全卷积神经网络（FCNs）在许多密集标记问题中表现出突出的性能。这些成功的关键支柱是从卷积层的特征中挖掘相关信息。但是，如何更好地聚合多级卷积特征映射来显着检测物体。在这项工作中，我们提出了一个用于显着物体检测的通用聚合多级卷积特征框架Amulet。我们的框架首先将多级特征地图集成为多个分辨率，同时包含粗略的语义和细节。然后自适应地学习在每个分辨率下组合这些特征图，并预测具有组合特征的显着图。最后，预测结果被有效地融合以生成最终的显着图。另外，为了实现准确的边界推理和语义增强，低层次的边缘感知特征映射和低分辨率特征的预测结果被递归地嵌入到学习框架中。通过以这种高效和灵活的方式聚合多级卷积特征，所提出的显着性模型提供了准确的显着对象标记。全面的实验表明，我们的方法在几乎所有比较的评估指标方面都能够有效地抵抗最先进的方法。

##### URL
[https://arxiv.org/abs/1708.02001](https://arxiv.org/abs/1708.02001)

##### PDF
[https://arxiv.org/pdf/1708.02001](https://arxiv.org/pdf/1708.02001)

