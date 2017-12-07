---
layout: post
title: "Anatomically Constrained Neural Networks : Application to Cardiac Image Enhancement and Segmentation"
date: 2017-12-05 23:04:00
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation GAN Image_Enhancement Classification Prediction
author: Ozan Oktay, Enzo Ferrante, Konstantinos Kamnitsas, Mattias Heinrich, Wenjia Bai, Jose Caballero, Stuart Cook, Antonio de Marvao, Timothy Dawes, Declan O&#x27;Regan, Bernhard Kainz, Ben Glocker, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Incorporation of prior knowledge about organ shape and location is key to improve performance of image analysis approaches. In particular, priors can be useful in cases where images are corrupted and contain artefacts due to limitations in image acquisition. The highly constrained nature of anatomical objects can be well captured with learning based techniques. However, in most recent and promising techniques such as CNN based segmentation it is not obvious how to incorporate such prior knowledge. State-of-the-art methods operate as pixel-wise classifiers where the training objectives do not incorporate the structure and inter-dependencies of the output. To overcome this limitation, we propose a generic training strategy that incorporates anatomical prior knowledge into CNNs through a new regularisation model, which is trained end-to-end. The new framework encourages models to follow the global anatomical properties of the underlying anatomy (e.g. shape, label structure) via learned non-linear representations of the shape. We show that the proposed approach can be easily adapted to different analysis tasks (e.g. image enhancement, segmentation) and improve the prediction accuracy of the state-of-the-art models. The applicability of our approach is shown on multi-modal cardiac datasets and public benchmarks. Additionally, we demonstrate how the learned deep models of 3D shapes can be interpreted and used as biomarkers for classification of cardiac pathologies.

##### Abstract (translated by Google)
结合关于器官形状和位置的先前知识是提高图像分析方法的性能的关键。特别是，由于图像采集的限制，在图像被破坏并且包含伪影的情况下，先验图像可以是有用的。基于学习的技术可以很好地捕捉解剖对象的高度约束性。然而，在最新的和有前途的技术，如基于CNN的分割，如何纳入这些先前的知识并不明显。最先进的方法是像素分类器，其训练目标不包含输出的结构和相互依赖关系。为了克服这个局限性，我们提出了一种通用的训练策略，通过新的正则化模型将解剖学的先验知识整合到CNNs中，该模型是端对端训练的。新的框架鼓励模型通过形状学习的非线性表示来遵循底层解剖学的全局解剖学特性（例如形状，标签结构）。我们表明，提出的方法可以很容易地适应不同的分析任务（如图像增强，分割），并提高了最先进的模型的预测准确性。我们的方法适用性显示在多模心脏数据集和公共基准。此外，我们演示如何学习3D形状的深层模型可以解释和用作心脏病理分类的生物标志物。

##### URL
[http://arxiv.org/abs/1705.08302](http://arxiv.org/abs/1705.08302)

##### PDF
[http://arxiv.org/pdf/1705.08302](http://arxiv.org/pdf/1705.08302)

