---
layout: post
title: "Learning to Predict Indoor Illumination from a Single Image"
date: 2017-11-21 08:32:24
categories: arXiv_CV
tags: arXiv_CV
author: Marc-André Gardner, Kalyan Sunkavalli, Ersin Yumer, Xiaohui Shen, Emiliano Gambaretto, Christian Gagné, Jean-François Lalonde
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an automatic method to infer high dynamic range illumination from a single, limited field-of-view, low dynamic range photograph of an indoor scene. In contrast to previous work that relies on specialized image capture, user input, and/or simple scene models, we train an end-to-end deep neural network that directly regresses a limited field-of-view photo to HDR illumination, without strong assumptions on scene geometry, material properties, or lighting. We show that this can be accomplished in a three step process: 1) we train a robust lighting classifier to automatically annotate the location of light sources in a large dataset of LDR environment maps, 2) we use these annotations to train a deep neural network that predicts the location of lights in a scene from a single limited field-of-view photo, and 3) we fine-tune this network using a small dataset of HDR environment maps to predict light intensities. This allows us to automatically recover high-quality HDR illumination estimates that significantly outperform previous state-of-the-art methods. Consequently, using our illumination estimates for applications like 3D object insertion, we can achieve results that are photo-realistic, which is validated via a perceptual user study.

##### Abstract (translated by Google)
我们提出了一种自动的方法来从一个单一的，有限的视野，低动态范围的室内场景照片推断高动态范围照明。与之前的依赖于专业图像捕获，用户输入和/或简单场景模型的工作相比，我们训练了一个端到端的深度神经网络，将有限的视野照片直接回归到HDR照明，而没有强烈的关于场景几何，材料特性或照明的假设。我们表明，这可以在三个步骤中完成：1）我们训练一个强大的照明分类器，自动注释光源在LDR环境地图的大型数据集中的位置，2）我们使用这些注释来训练深度神经网络通过单个有限的视场照片预测场景中灯光的位置; 3）使用HDR环境地图的小数据集对该网络进行微调，以预测光强度。这使我们能够自动恢复高质量的HDR照度估算值，这些估算值明显优于先前的最先进的方法。因此，我们使用我们的照明估计来应用3D对象插入，我们可以获得相片逼真的效果，这是通过感知用户研究来验证的。

##### URL
[https://arxiv.org/abs/1704.00090](https://arxiv.org/abs/1704.00090)

##### PDF
[https://arxiv.org/pdf/1704.00090](https://arxiv.org/pdf/1704.00090)

