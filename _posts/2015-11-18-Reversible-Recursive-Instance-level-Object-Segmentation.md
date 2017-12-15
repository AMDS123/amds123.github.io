---
layout: post
title: "Reversible Recursive Instance-level Object Segmentation"
date: 2015-11-18 06:49:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Xiaodan Liang, Yunchao Wei, Xiaohui Shen, Zequn Jie, Jiashi Feng, Liang Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel Reversible Recursive Instance-level Object Segmentation (R2-IOS) framework to address the challenging instance-level object segmentation task. R2-IOS consists of a reversible proposal refinement sub-network that predicts bounding box offsets for refining the object proposal locations, and an instance-level segmentation sub-network that generates the foreground mask of the dominant object instance in each proposal. By being recursive, R2-IOS iteratively optimizes the two sub-networks during joint training, in which the refined object proposals and improved segmentation predictions are alternately fed into each other to progressively increase the network capabilities. By being reversible, the proposal refinement sub-network adaptively determines an optimal number of refinement iterations required for each proposal during both training and testing. Furthermore, to handle multiple overlapped instances within a proposal, an instance-aware denoising autoencoder is introduced into the segmentation sub-network to distinguish the dominant object from other distracting instances. Extensive experiments on the challenging PASCAL VOC 2012 benchmark well demonstrate the superiority of R2-IOS over other state-of-the-art methods. In particular, the $\text{AP}^r$ over $20$ classes at $0.5$ IoU achieves $66.7\%$, which significantly outperforms the results of $58.7\%$ by PFN~\cite{PFN} and $46.3\%$ by~\cite{liu2015multi}.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个新颖的可逆递归实例级对象分割（R2-IOS）框架来解决具有挑战性的实例级对象分割任务。 R2-IOS由一个可逆提议细化子网络和一个实例级别分割子网络组成，每个提案中的主导对象实例的前景掩码都是由实例级分割子网络组成的。通过递归，R2-IOS在联合训练期间迭代地优化两个子网络，其中经过改进的对象提议和改进的分割预测彼此交替地馈送以逐步增加网络能力。通过可逆，提案细化子网络在培训和测试期间自适应地确定每个提案所需的最佳细化迭代次数。此外，为了处理提案中的多个重叠实例，将实例感知的去噪自动编码器引入到分割子网络中以将主导对象与其他干扰实例区分开来。在具有挑战性的PASCAL VOC 2012基准测试中的大量实验证明了R2-IOS优于其他最先进的方法的优越性。特别是$ 0.5 $ IoU的$ \ text {AP} ^ r $超过$ 20 $类的成本$ 66.7 \％$，明显优于PFN〜\ cite {PFN}的$ 58.7 \％$和$ 46.3 \％$由〜\ {引用} liu2015multi。

##### URL
[https://arxiv.org/abs/1511.04517](https://arxiv.org/abs/1511.04517)

##### PDF
[https://arxiv.org/pdf/1511.04517](https://arxiv.org/pdf/1511.04517)

