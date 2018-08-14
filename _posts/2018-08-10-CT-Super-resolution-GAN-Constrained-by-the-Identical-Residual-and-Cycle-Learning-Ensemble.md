---
layout: post
title: "CT Super-resolution GAN Constrained by the Identical, Residual, and Cycle Learning Ensemble"
date: 2018-08-10 05:33:23
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN Deep_Learning Quantitative
author: Chenyu You, Yi Zhang, Xiaoliu Zhang, Guang Li, Shenghong Ju, Zhen Zhao, Zhuiyang Zhang, Wenxiang Cong, Punam K. Saha, Ge Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Computed tomography (CT) is a popular medical imaging modality for screening, diagnosis, and image-guided therapy. However, CT has its limitations, especially involved ionizing radiation dose. Practically, it is highly desirable to have ultrahigh quality CT imaging for fine structural details at a minimized radiation dosage. In this paper, we propose a semi-supervised deep learning approach to recover high-resolution (HR) CT images from low-resolution (LR) counterparts. Especially, with the generative adversarial network (GAN) as the basic component, we enforce the cycle-consistency in terms of the Wasserstein distance to establish a nonlinear end-to-end mapping from noisy LR input images to denoised HR outputs. In this deep imaging process, we incorporate deep convolutional neural network (CNNs), residual learning, and network in network techniques for feature extraction and restoration. In contrast to the current trend of increasing network depth and complexity to boost the CT imaging performance, which limit its real-world applications by imposing considerable computational and memory overheads, we apply a parallel 1x1 CNN to reduce the dimensionality of the output of the hidden layer. Furthermore, we optimize the number of layers and the number of filters for each CNN layer. Quantitative and qualitative evaluations demonstrate that our proposed model is accurate, efficient and robust for SR image restoration from noisy LR input images. In particular, we validate our composite SR networks on two large-scale CT datasets, and obtain very encouraging results as compared to the other state-of-the-art methods.

##### Abstract (translated by Google)
计算机断层扫描（CT）是一种用于筛查，诊断和图像引导治疗的流行医学成像模式。然而，CT有其局限性，尤其涉及电离辐射剂量。实际上，非常希望在最小化的辐射剂量下具有超高质量的CT成像以获得精细的结构细节。在本文中，我们提出了一种半监督深度学习方法，用于从低分辨率（LR）对应物恢复高分辨率（HR）CT图像。特别是，以生成对抗网络（GAN）为基本组件，我们根据Wasserstein距离强制执行循环一致性，以建立从噪声LR输入图像到去噪HR输出的非线性端到端映射。在这个深度成像过程中，我们将深度卷积神经网络（CNN），残差学习和网络技术结合到网络技术中进行特征提取和恢复。与当前增加网络深度和复杂性以提高CT成像性能的趋势形成对比，后者通过施加可观的计算和内存开销来限制其实际应用，我们应用并行1x1 CNN来减少隐藏输出的维数层。此外，我们优化每个CNN层的层数和过滤器数量。定量和定性评估表明，我们提出的模型对于从嘈杂的LR输入图像恢复SR图像是准确，有效和稳健的。特别是，我们在两个大型CT数据集上验证了我们的复合SR网络，与其他最先进的方法相比，获得了非常令人鼓舞的结果。

##### URL
[http://arxiv.org/abs/1808.04256](http://arxiv.org/abs/1808.04256)

##### PDF
[http://arxiv.org/pdf/1808.04256](http://arxiv.org/pdf/1808.04256)

