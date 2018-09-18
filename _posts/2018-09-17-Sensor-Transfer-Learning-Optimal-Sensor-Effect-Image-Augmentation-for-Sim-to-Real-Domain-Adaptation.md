---
layout: post
title: "Sensor Transfer: Learning Optimal Sensor Effect Image Augmentation for Sim-to-Real Domain Adaptation"
date: 2018-09-17 14:44:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Alexandra Carlson, Katherine A. Skinner, Ram Vasudevan, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
Performance on benchmark datasets has drastically improved with advances in deep learning. Still, cross- dataset generalization performance remains relatively low due to the domain shift that can occur between two different datasets. This domain shift is especially exaggerated between synthetic and real datasets. Significant research has been done to reduce this gap, specifically via modeling variation in the spatial layout of a scene, such as occlusions, and scene environmental factors, such as time of day and weather effects. However, few works have addressed modeling the variation in the sensor domain as a means of reducing the synthetic to real domain gap. The camera or sensor used to capture a dataset introduces artifacts into the image data that are unique to the sensor model, suggesting that sensor effects may also contribute to domain shift. To address this, we propose a learned augmentation network composed of physically-based augmentation functions. Our proposed augmentation pipeline transfers specific effects of the sensor model --chromatic aberration, blur, exposure, noise, and color temperature-- from a real dataset to a synthetic dataset. We provide experiments that demonstrate that augmenting synthetic training datasets with the proposed learned augmentation framework reduces the domain gap between synthetic and real domains for object detection in urban driving scenes.

##### Abstract (translated by Google)
随着深度学习的进步，基准数据集的性能得到了显着提高。尽管如此，由于两个不同数据集之间可能发生的域移位，跨数据集泛化性能仍然相对较低。这种域转换在合成数据集和真实数据集之间尤为夸张。已经进行了大量研究以减少这种差距，特别是通过建模场景空间布局的变化（例如遮挡）和场景环境因素（例如一天中的时间和天气效果）。然而，很少有工作涉及对传感器域中的变化进行建模，作为减少合成域与实际域间隙的手段。用于捕获数据集的相机或传感器将伪像引入到传感器模型独有的图像数据中，这表明传感器效应也可能有助于域移位。为了解决这个问题，我们提出了一种由基于物理的增强功能组成的学习增强网络。我们提出的增强管道将传感器模型的特定效果 - 色差，模糊，曝光，噪声和色温 - 从真实数据集转移到合成数据集。我们提供的实验证明，利用所提出的学习增强框架来增强合成训练数据集，减少了城市驾驶场景中物体检测的合成域和真实域之间的领域差距。

##### URL
[http://arxiv.org/abs/1809.06256](http://arxiv.org/abs/1809.06256)

##### PDF
[http://arxiv.org/pdf/1809.06256](http://arxiv.org/pdf/1809.06256)

