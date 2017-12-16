---
layout: post
title: "Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning"
date: 2017-04-18 19:49:29
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Tien-Ju Yang, Yu-Hsin Chen, Vivienne Sze
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) are indispensable to state-of-the-art computer vision algorithms. However, they are still rarely deployed on battery-powered mobile devices, such as smartphones and wearable gadgets, where vision algorithms can enable many revolutionary real-world applications. The key limiting factor is the high energy consumption of CNN processing due to its high computational complexity. While there are many previous efforts that try to reduce the CNN model size or amount of computation, we find that they do not necessarily result in lower energy consumption, and therefore do not serve as a good metric for energy cost estimation. To close the gap between CNN design and energy consumption optimization, we propose an energy-aware pruning algorithm for CNNs that directly uses energy consumption estimation of a CNN to guide the pruning process. The energy estimation methodology uses parameters extrapolated from actual hardware measurements that target realistic battery-powered system setups. The proposed layer-by-layer pruning algorithm also prunes more aggressively than previously proposed pruning methods by minimizing the error in output feature maps instead of filter weights. For each layer, the weights are first pruned and then locally fine-tuned with a closed-form least-square solution to quickly restore the accuracy. After all layers are pruned, the entire network is further globally fine-tuned using back-propagation. With the proposed pruning method, the energy consumption of AlexNet and GoogLeNet are reduced by 3.7x and 1.6x, respectively, with less than 1% top-5 accuracy loss. Finally, we show that pruning the AlexNet with a reduced number of target classes can greatly decrease the number of weights but the energy reduction is limited. Energy modeling tool and energy-aware pruned models available at this http URL

##### Abstract (translated by Google)
深卷积神经网络（CNN）是最先进的计算机视觉算法所不可或缺的。但是，他们仍然很少部署在电池供电的移动设备上，例如智能手机和可穿戴设备，视觉算法可以实现许多革命性的现实应用。关键的限制因素是CNN处理的高能量消耗，因为其计算复杂度高。虽然以前有许多尝试减小CNN模型大小或计算量的努力，但是我们发现它们不一定导致较低的能量消耗，因此不能作为能量成本估计的良好度量。为了弥补CNN设计和能耗优化之间的差距，我们提出了一种能量感知的CNN修剪算法，直接利用CNN的能耗估算来指导修剪过程。能量估算方法使用从实际硬件测量中推断出的参数，这些参数是以实际的电池供电系统设置为目标的。通过最小化输出特征映射中的误差而不是滤波器权重，所提出的逐层修剪算法也比先前提出的修剪方法更积极修剪。对于每一层，首先修剪权重，然后使用封闭形式的最小二乘解来局部微调以快速恢复精度。在所有层被修剪后，整个网络进一步通过反向传播进行全局微调。使用修剪方法，AlexNet和GoogLeNet的能耗分别降低了3.7倍和1.6倍，精度损失前5％的能耗不到1％。最后，我们显示修剪AlexNet数量减少的目标类可以大大减少权重的数量，但能量减少是有限的。能源建模工具和能源感知修剪模型可在这个HTTP URL

##### URL
[https://arxiv.org/abs/1611.05128](https://arxiv.org/abs/1611.05128)

##### PDF
[https://arxiv.org/pdf/1611.05128](https://arxiv.org/pdf/1611.05128)

