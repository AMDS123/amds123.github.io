---
layout: post
title: "Poseidon: An Efficient Communication Architecture for Distributed Deep Learning on GPU Clusters"
date: 2017-06-11 01:11:06
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Deep_Learning
author: Hao Zhang, Zeyu Zheng, Shizhen Xu, Wei Dai, Qirong Ho, Xiaodan Liang, Zhiting Hu, Jinliang Wei, Pengtao Xie, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models can take weeks to train on a single GPU-equipped machine, necessitating scaling out DL training to a GPU-cluster. However, current distributed DL implementations can scale poorly due to substantial parameter synchronization over the network, because the high throughput of GPUs allows more data batches to be processed per unit time than CPUs, leading to more frequent network synchronization. We present Poseidon, an efficient communication architecture for distributed DL on GPUs. Poseidon exploits the layered model structures in DL programs to overlap communication and computation, reducing bursty network communication. Moreover, Poseidon uses a hybrid communication scheme that optimizes the number of bytes required to synchronize each layer, according to layer properties and the number of machines. We show that Poseidon is applicable to different DL frameworks by plugging Poseidon into Caffe and TensorFlow. We show that Poseidon enables Caffe and TensorFlow to achieve 15.5x speed-up on 16 single-GPU machines, even with limited bandwidth (10GbE) and the challenging VGG19-22K network for image classification. Moreover, Poseidon-enabled TensorFlow achieves 31.5x speed-up with 32 single-GPU machines on Inception-V3, a 50% improvement over the open-source TensorFlow (20x speed-up).

##### Abstract (translated by Google)
深度学习模型可能需要数周的时间才能在单个配备GPU的机器上进行训练，因此需要将DL训练扩展到GPU群集。然而，由于GPU的高吞吐量允许每单位时间比CPU处理更多的数据批次，导致更频繁的网络同步，所以当前的分布式DL实现可以通过网络上的实质参数同步而缩小。我们展示了Poseidon，一种用于GPU上分布式DL的高效通信架构。波塞冬利用DL程序中的分层模型结构来重叠通信和计算，减少突发的网络通信。此外，波塞冬使用混合通信方案，根据图层属性和机器数量优化每层同步所需的字节数。我们展示了波塞冬通过将波塞冬插入Caffe和TensorFlow来适用于不同的DL框架。我们展示了Poseidon使得Caffe和TensorFlow能够在16台单GPU机器上实现15.5倍的加速，即使在有限的带宽（10GbE）以及用于图像分类的具有挑战性的VGG19-22K网络中。此外，使用Poseidon技术的TensorFlow在Inception-V3上使用32台单GPU机器可实现31.5倍的加速，比开源TensorFlow（20倍加速）提高了50％。

##### URL
[https://arxiv.org/abs/1706.03292](https://arxiv.org/abs/1706.03292)

##### PDF
[https://arxiv.org/pdf/1706.03292](https://arxiv.org/pdf/1706.03292)

