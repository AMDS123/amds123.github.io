---
layout: post
title: "MixedPeds: Pedestrian Detection in Unannotated Videos using Synthetically Generated Human-agents for Training"
date: 2017-11-11 19:12:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Ernest C. Cheung, Tsan Kwong Wong, Aniket Bera, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method for training pedestrian detectors on an unannotated set of images. We produce a mixed reality dataset that is composed of real-world background images and synthetically generated static human-agents. Our approach is general, robust, and makes no other assumptions about the unannotated dataset regarding the number or location of pedestrians. We automatically extract from the dataset: i) the vanishing point to calibrate the virtual camera, and ii) the pedestrians' scales to generate a Spawn Probability Map, which is a novel concept that guides our algorithm to place the pedestrians at appropriate locations. After putting synthetic human-agents in the unannotated images, we use these augmented images to train a Pedestrian Detector, with the annotations generated along with the synthetic agents. We conducted our experiments using Faster R-CNN by comparing the detection results on the unannotated dataset performed by the detector trained using our approach and detectors trained with other manually labeled datasets. We showed that our approach improves the average precision by 5-13% over these detectors.

##### Abstract (translated by Google)
我们提出了一个新的方法来训练行人检测器在一组未经注释的图像上。我们产生一个由真实世界的背景图像和综合生成的静态人工智能体组成的混合现实数据集。我们的方法是一般的，强大的，并没有任何关于行人的数量或位置未注释的数据集的其他假设。我们从数据集中自动提取：i）校准虚拟摄像机的消失点，以及ii）行人的尺度，以生成Spawn概率图，这是一个新颖的概念，指导我们的算法将行人放置在适当的位置。在将未加注释的图像放入合成人工代理之后，我们使用这些增强图像来训练一个行人检测器，其中注释与合成代理一起产生。我们通过比较由使用我们的方法训练的检测器执行的未注释数据集的检测结果和使用其他手动标记的数据集训练的检测器，使用更快的R-CNN进行我们的实验。我们表明，我们的方法提高了这些检测器的平均精度5-13％。

##### URL
[https://arxiv.org/abs/1707.09100](https://arxiv.org/abs/1707.09100)

##### PDF
[https://arxiv.org/pdf/1707.09100](https://arxiv.org/pdf/1707.09100)

