---
layout: post
title: "Coordinating Filters for Faster Deep Neural Networks"
date: 2017-07-25 17:54:31
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Wei Wen, Cong Xu, Chunpeng Wu, Yandan Wang, Yiran Chen, Hai Li
mathjax: true
---

* content
{:toc}

##### Abstract
Very large-scale Deep Neural Networks (DNNs) have achieved remarkable successes in a large variety of computer vision tasks. However, the high computation intensity of DNNs makes it challenging to deploy these models on resource-limited systems. Some studies used low-rank approaches that approximate the filters by low-rank basis to accelerate the testing. Those works directly decomposed the pre-trained DNNs by Low-Rank Approximations (LRA). How to train DNNs toward lower-rank space for more efficient DNNs, however, remains as an open area. To solve the issue, in this work, we propose Force Regularization, which uses attractive forces to enforce filters so as to coordinate more weight information into lower-rank space. We mathematically and empirically verify that after applying our technique, standard LRA methods can reconstruct filters using much lower basis and thus result in faster DNNs. The effectiveness of our approach is comprehensively evaluated in ResNets, AlexNet, and GoogLeNet. In AlexNet, for example, Force Regularization gains 2x speedup on modern GPU without accuracy loss and 4.05x speedup on CPU by paying small accuracy degradation. Moreover, Force Regularization better initializes the low-rank DNNs such that the fine-tuning can converge faster toward higher accuracy. The obtained lower-rank DNNs can be further sparsified, proving that Force Regularization can be integrated with state-of-the-art sparsity-based acceleration methods. Source code is available in this https URL

##### Abstract (translated by Google)
非常大规模的深度神经网络（DNN）在各种计算机视觉任务中取得了显着的成功。然而，DNN的高计算强度使得将这些模型部署在资源有限的系统上具有挑战性。一些研究使用低阶方法，以低阶基础来近似滤波器以加速测试。这些作品通过低阶逼近（LRA）直接分解预训练的DNN。如何将DNNs训练到更低层次的空间以获得更高效的DNN，但是仍然是一个开放的领域。为了解决这个问题，本文提出了“力量正则化”，即利用吸引力来强化过滤器，从而将更多的权重信息协调到更低层次的空间。我们在数学和经验上验证，应用我们的技术后，标准的LRA方法可以使用更低的基础重建滤波器，从而导致更快的DNN。我们的方法的有效性在ResNet，AlexNet和GoogLeNet全面评估。例如，在AlexNet中，Force Regularization在现代GPU上获得了2倍的提速，没有精确度的损失，而在CPU上则提高了4.05倍的速度。而且，力正则化可以更好地初始化低秩DNN，这样微调可以更快地收敛到更高的精度。所获得的较低等级的DNN可以进一步稀疏，证明力正则化可以与最先进的基于稀疏度的加速度方法相结合。源代码在此https URL中可用

##### URL
[https://arxiv.org/abs/1703.09746](https://arxiv.org/abs/1703.09746)

##### PDF
[https://arxiv.org/pdf/1703.09746](https://arxiv.org/pdf/1703.09746)

