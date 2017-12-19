---
layout: post
title: "Poseidon: A System Architecture for Efficient GPU-based Deep Learning on Multiple Machines"
date: 2015-12-19 09:55:37
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Recognition
author: Hao Zhang, Zhiting Hu, Jinliang Wei, Pengtao Xie, Gunhee Kim, Qirong Ho, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) has achieved notable successes in many machine learning tasks. A number of frameworks have been developed to expedite the process of designing and training deep neural networks (DNNs), such as Caffe, Torch and Theano. Currently they can harness multiple GPUs on a single machine, but are unable to use GPUs that are distributed across multiple machines; as even average-sized DNNs can take days to train on a single GPU with 100s of GBs to TBs of data, distributed GPUs present a prime opportunity for scaling up DL. However, the limited bandwidth available on commodity Ethernet networks presents a bottleneck to distributed GPU training, and prevents its trivial realization. To investigate how to adapt existing frameworks to efficiently support distributed GPUs, we propose Poseidon, a scalable system architecture for distributed inter-machine communication in existing DL frameworks. We integrate Poseidon with Caffe and evaluate its performance at training DNNs for object recognition. Poseidon features three key contributions that accelerate DNN training on clusters: (1) a three-level hybrid architecture that allows Poseidon to support both CPU-only and GPU-equipped clusters, (2) a distributed wait-free backpropagation (DWBP) algorithm to improve GPU utilization and to balance communication, and (3) a structure-aware communication protocol (SACP) to minimize communication overheads. We empirically show that Poseidon converges to same objectives as a single machine, and achieves state-of-art training speedup across multiple models and well-established datasets using a commodity GPU cluster of 8 nodes (e.g. 4.5x speedup on AlexNet, 4x on GoogLeNet, 4x on CIFAR-10). On the much larger ImageNet22K dataset, Poseidon with 8 nodes achieves better speedup and competitive accuracy to recent CPU-based distributed systems such as Adam and Le et al., which use 10s to 1000s of nodes.

##### Abstract (translated by Google)
深度学习（DL）在许多机器学习任务中取得了显着的成功。已经开发了一些框架来加速深度神经网络（DNN）的设计和培训，如Caffe，Torch和Theano。目前，他们可以在一台机器上利用多个GPU，但无法使用分布在多台机器上的GPU;因为即使是平均规模的DNN也可能需要数天的时间才能在单个GPU上训练数百GB的数据，但分布式GPU为扩展DL提供了一个主要机会。然而，商用以太网上可用的有限带宽是分布式GPU培训的一个瓶颈，并且阻碍了其微不足道的实现。为了研究如何调整现有的框架来有效地支持分布式GPU，我们提出了Poseidon，这是一种用于现有DL框架中的分布式机器间通信的可扩展系统架构。我们整合了Poseidon和Caffe，并在训练DNNs上评估其性能，以便进行物体识别。 （1）三级混合体系结构，允许Poseidon支持仅CPU和GPU配置的簇，（2）分布式等待自由反向传播（DWBP）算法，以提高GPU利用率并平衡通信，以及（3）结构感知通信协议（SACP）以最小化通信开销。我们通过实验证明，波塞冬与单个机器相同的目标是一致的，并且使用一个包含8个节点的商品GPU集群在多个模型和完善的数据集上实现了最先进的训练速度（例如，AlexNet 4.5x加速，GoogLeNet 4x ，在CIFAR-10上是4倍）。在大得多的ImageNet22​​K数据集上，具有8个节点的Poseidon对于最近基于CPU的分布式系统（例如Adam和Le等人）使用10s到1000s的节点实现了更好的加速和竞争精度。

##### URL
[https://arxiv.org/abs/1512.06216](https://arxiv.org/abs/1512.06216)

##### PDF
[https://arxiv.org/pdf/1512.06216](https://arxiv.org/pdf/1512.06216)

