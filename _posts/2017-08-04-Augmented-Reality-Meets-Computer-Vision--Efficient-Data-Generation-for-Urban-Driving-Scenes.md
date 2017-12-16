---
layout: post
title: "Augmented Reality Meets Computer Vision : Efficient Data Generation for Urban Driving Scenes"
date: 2017-08-04 16:03:52
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Object_Detection Segmentation Deep_Learning Detection
author: Hassan Abu Alhaija, Siva Karthik Mustikovela, Lars Mescheder, Andreas Geiger, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
The success of deep learning in computer vision is based on availability of large annotated datasets. To lower the need for hand labeled images, virtually rendered 3D worlds have recently gained popularity. Creating realistic 3D content is challenging on its own and requires significant human effort. In this work, we propose an alternative paradigm which combines real and synthetic data for learning semantic instance segmentation and object detection models. Exploiting the fact that not all aspects of the scene are equally important for this task, we propose to augment real-world imagery with virtual objects of the target category. Capturing real-world images at large scale is easy and cheap, and directly provides real background appearances without the need for creating complex 3D models of the environment. We present an efficient procedure to augment real images with virtual objects. This allows us to create realistic composite images which exhibit both realistic background appearance and a large number of complex object arrangements. In contrast to modeling complete 3D environments, our augmentation approach requires only a few user interactions in combination with 3D shapes of the target object. Through extensive experimentation, we conclude the right set of parameters to produce augmented data which can maximally enhance the performance of instance segmentation models. Further, we demonstrate the utility of our approach on training standard deep models for semantic instance segmentation and object detection of cars in outdoor driving scenes. We test the models trained on our augmented data on the KITTI 2015 dataset, which we have annotated with pixel-accurate ground truth, and on Cityscapes dataset. Our experiments demonstrate that models trained on augmented imagery generalize better than those trained on synthetic data or models trained on limited amount of annotated real data.

##### Abstract (translated by Google)
计算机视觉深度学习的成功基于大量注释数据集的可用性。为了降低对手绘标签图像的需求，虚拟渲染的3D世界近来获得了普及。创建逼真的3D内容本身就具有挑战性，需要大量的人力。在这项工作中，我们提出了一个结合真实和合成数据的替代范例，用于学习语义实例分割和对象检测模型。利用不是所有场景都对这个任务同样重要的事实，我们建议用目标类别的虚拟物体来增加现实世界的图像。大规模捕捉真实世界的图像既简单又便宜，而且直接提供真实的背景外观，而无需创建复杂的环境三维模型。我们提出一个有效的程序来增加虚拟物体的真实图像。这使我们能够创造真实的复合图像，展现出逼真的背景外观和大量复杂的物体排列。与建模完整的3D环境相比，我们的增强方法仅需要少量的用户交互，并与目标对象的3D形状相结合。通过大量的实验，我们得出正确的参数集合来产生增强数据，这可以最大限度地提高实例分割模型的性能。此外，我们证明了我们的方法在训练室外驾驶场景中的车辆的语义实例分割和对象检测的标准深度模型上的实用性。我们在KITTI 2015数据集（我们已经用像素精确的地面实况注释）和Cityscapes数据集上测试了我们在增强数据上训练的模型。我们的实验证明，在增强图像上训练的模型比在有限数量的带注释的实际数据上训练的合成数据或模型训练的模型更一般化。

##### URL
[https://arxiv.org/abs/1708.01566](https://arxiv.org/abs/1708.01566)

##### PDF
[https://arxiv.org/pdf/1708.01566](https://arxiv.org/pdf/1708.01566)

