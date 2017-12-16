---
layout: post
title: "Out-of-focus: Learning Depth from Image Bokeh for Robotic Perception"
date: 2017-05-02 19:30:51
categories: arXiv_CV
tags: arXiv_CV CNN
author: Eric Cristofalo, Zijian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this project, we propose a novel approach for estimating depth from RGB images. Traditionally, most work uses a single RGB image to estimate depth, which is inherently difficult and generally results in poor performance, even with thousands of data examples. In this work, we alternatively use multiple RGB images that were captured while changing the focus of the camera's lens. This method leverages the natural depth information correlated to the different patterns of clarity/blur in the sequence of focal images, which helps distinguish objects at different depths. Since no such data set exists for learning this mapping, we collect our own data set using customized hardware. We then use a convolutional neural network for learning the depth from the stacked focal images. Comparative studies were conducted on both a standard RGBD data set and our own data set (learning from both single and multiple images), and results verified that stacked focal images yield better depth estimation than using just single RGB image.

##### Abstract (translated by Google)
在这个项目中，我们提出了一种从RGB图像中估计深度的新方法。传统上，大多数作品使用单一的RGB图像来估计深度，这本质上是困难的，并且即使在数千个数据示例下也通常导致性能较差。在这项工作中，我们可以选择使用在改变相机镜头焦点时拍摄的多个RGB图像。此方法利用与焦点图像序列中的不同清晰度/模糊模式相关的自然深度信息，这有助于区分不同深度的物体。由于不存在用于学习该映射的这样的数据集，我们使用定制的硬件来收集我们自己的数据集。然后我们使用卷积神经网络来从堆叠的焦点图像中学习深度。在标准RGBD数据集和我们自己的数据集（从单幅图像和多幅图像学习）上进行了比较研究，结果证实堆叠式聚焦图像产生比仅使用单个RGB图像更好的深度估计。

##### URL
[https://arxiv.org/abs/1705.01152](https://arxiv.org/abs/1705.01152)

##### PDF
[https://arxiv.org/pdf/1705.01152](https://arxiv.org/pdf/1705.01152)

