---
layout: post
title: "Energy-based Tuning of Convolutional Neural Networks on Multi-GPUs"
date: 2018-08-01 12:08:02
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Recognition
author: Francisco M. Castro, Nicolás Guil, Manuel J. Marín-Jiménez, Jesús Pérez-Serrano, Manuel Ujaldón
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning (DL) applications are gaining momentum in the realm of Artificial Intelligence, particularly after GPUs have demonstrated remarkable skills for accelerating their challenging computational requirements. Within this context, Convolutional Neural Network (CNN) models constitute a representative example of success on a wide set of complex applications, particularly on datasets where the target can be represented through a hierarchy of local features of increasing semantic complexity. In most of the real scenarios, the roadmap to improve results relies on CNN settings involving brute force computation, and researchers have lately proven Nvidia GPUs to be one of the best hardware counterparts for acceleration. Our work complements those findings with an energy study on critical parameters for the deployment of CNNs on flagship image and video applications: object recognition and people identification by gait, respectively. We evaluate energy consumption on four different networks based on the two most popular ones (ResNet/AlexNet): ResNet (167 layers), a 2D CNN (15 layers), a CaffeNet (25 layers) and a ResNetIm (94 layers) using batch sizes of 64, 128 and 256, and then correlate those with speed-up and accuracy to determine optimal settings. Experimental results on a multi-GPU server endowed with twin Maxwell and twin Pascal Titan X GPUs demonstrate that energy correlates with performance and that Pascal may have up to 40% gains versus Maxwell. Larger batch sizes extend performance gains and energy savings, but we have to keep an eye on accuracy, which sometimes shows a preference for small batches. We expect this work to provide a preliminary guidance for a wide set of CNN and DL applications in modern HPC times, where the GFLOPS/w ratio constitutes the primary goal.

##### Abstract (translated by Google)
深度学习（DL）应用程序在人工智能领域正在获得动力，尤其是在GPU已经展示了加速其具有挑战性的计算要求的卓越技能之后。在此背景下，卷积神经网络（CNN）模型构成了在广泛的复杂应用程序上成功的代表性示例，特别是在数据集上，其中目标可以通过增加语义复杂性的局部特征的层次结构来表示。在大多数实际场景中，改进结果的路线图依赖于涉及强力计算的CNN设置，研究人员最近证明Nvidia GPU是加速的最佳硬件对应物之一。我们的工作通过对旗舰图像和视频应用中CNN部署的关键参数的能量研究进行了补充：物体识别和步态识别人员。我们基于两个最受欢迎的网络（ResNet / AlexNet）评估四个不同网络的能耗：ResNet（167层），2D CNN（15层），CaffeNet（25层）和ResNetIm（94层）使用批次尺寸为64,128和256，然后将它们与加速和精度相关联，以确定最佳设置。在具有双Maxwell和双Pascal Titan X GPU的多GPU服务器上的实验结果表明，能量与性能相关，并且Pascal可能比Maxwell高出40％。较大的批量大小可以提高性能并节省能源，但我们必须密切关注准确性，有时候会显示出对小批量的偏好。我们希望这项工作能够为现代HPC时代的各种CNN和DL应用提供初步指导，其中GFLOPS / w比率是主要目标。

##### URL
[https://arxiv.org/abs/1808.00286](https://arxiv.org/abs/1808.00286)

##### PDF
[https://arxiv.org/pdf/1808.00286](https://arxiv.org/pdf/1808.00286)

