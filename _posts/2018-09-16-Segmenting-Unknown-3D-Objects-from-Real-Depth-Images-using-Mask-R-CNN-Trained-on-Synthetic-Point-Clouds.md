---
layout: post
title: "Segmenting Unknown 3D Objects from Real Depth Images using Mask R-CNN Trained on Synthetic Point Clouds"
date: 2018-09-16 07:08:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking
author: Michael Danielczuk, Matthew Matl, Saurabh Gupta, Andrew Li, Andrew Lee, Jeffrey Mahler, Ken Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to segment unknown objects in depth images has potential to enhance robot skills in grasping and object tracking. Recent computer vision research has demonstrated that Mask R-CNN can be trained to segment specific categories of objects in RGB images when massive hand labeled datasets are available. As generating these datasets is time-consuming, we instead train with synthetic depth images. Many robots now use depth sensors, and recent results suggest training on synthetic depth data can generalize well to the real world. We present a method for automated dataset generation and rapidly generate a training dataset of 50k depth images and 320k object masks synthetically using simulated scenes of 3D CAD models. We train a variant of Mask R-CNN on the generated dataset to perform category-agnostic instance segmentation without hand-labeled data. We evaluate the trained network, which we refer to as Synthetic Depth (SD) Mask R-CNN, on a set of real, high-resolution images of challenging, densely cluttered bins containing objects with highly-varied geometry. SD Mask R-CNN outperforms point cloud clustering baselines by an absolute 15% in Average Precision and 20% in Average Recall, and achieves performance levels similar to a Mask RCNN trained on a massive, hand-labeled RGB dataset and fine-tuned on real images from the experimental setup. The network also generalizes well to a lower-resolution depth sensor. We deploy the model in an instance-specific grasping pipeline to demonstrate its usefulness in a robotics application. Code, the synthetic training dataset, and supplementary material are available at https://bit.ly/2letCuE .

##### Abstract (translated by Google)
在深度图像中分割未知对象的能力有可能增强抓取和对象跟踪中的机器人技能。最近的计算机视觉研究表明，当大量手工标记数据集可用时，可以训练Mask R-CNN在RGB图像中分割特定类别的对象。由于生成这些数据集非常耗时，因此我们使用合成深度图像进行训练。现在许多机器人都使用深度传感器，最近的结果表明，对合成深度数据的训练可以很好地推广到现实世界。我们提出了一种自动生成数据集的方法，并使用3D CAD模型的模拟场景，快速生成50k深度图像和320k对象掩模的训练数据集。我们在生成的数据集上训练Mask R-CNN的变体，以执行不带手标记数据的类别无关的实例分割。我们评估训练的网络，我们将其称为合成深度（SD）掩模R-CNN，在一组真实的高分辨率图像上，这些图像包含具有高度变化的几何形状的具有挑战性的密集杂乱的箱子。 SD掩模R-CNN的平均精度绝对值为15％，平均召回率为20％，性能水平类似于在大量手工标记的RGB数据集上训练的掩码RCNN，并在实际上进行微调来自实验装置的图像。该网络还可以很好地推广到分辨率较低的深度传感器。我们将模型部署在特定于实例的抓取管道中，以展示其在机器人应用程序中的有用性。代码，综合训练数据集和补充材料可在https://bit.ly/2letCuE获得。

##### URL
[http://arxiv.org/abs/1809.05825](http://arxiv.org/abs/1809.05825)

##### PDF
[http://arxiv.org/pdf/1809.05825](http://arxiv.org/pdf/1809.05825)

