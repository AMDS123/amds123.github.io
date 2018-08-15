---
layout: post
title: "Neural Network Encapsulation"
date: 2018-08-11 04:36:53
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Hongyang Li, Xiaoyang Guo, Bo Dai, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
A capsule is a collection of neurons which represents different variants of a pattern in the network. The routing scheme ensures only certain capsules which resemble lower counterparts in the higher layer should be activated. However, the computational complexity becomes a bottleneck for scaling up to larger networks, as lower capsules need to correspond to each and every higher capsule. To resolve this limitation, we approximate the routing process with two branches: a master branch which collects primary information from its direct contact in the lower layer and an aide branch that replenishes master based on pattern variants encoded in other lower capsules. Compared with previous iterative and unsupervised routing scheme, these two branches are communicated in a fast, supervised and one-time pass fashion. The complexity and runtime of the model are therefore decreased by a large margin. Motivated by the routing to make higher capsule have agreement with lower capsule, we extend the mechanism as a compensation for the rapid loss of information in nearby layers. We devise a feedback agreement unit to send back higher capsules as feedback. It could be regarded as an additional regularization to the network. The feedback agreement is achieved by comparing the optimal transport divergence between two distributions (lower and higher capsules). Such an add-on witnesses a unanimous gain in both capsule and vanilla networks. Our proposed EncapNet performs favorably better against previous state-of-the-arts on CIFAR10/100, SVHN and a subset of ImageNet.

##### Abstract (translated by Google)
胶囊是神经元的集合，其代表网络中模式的不同变体。路由方案确保仅激活类似于较高层中的较低对应物的某些胶囊。然而，计算复杂性成为扩展到更大网络的瓶颈，因为更低的胶囊需要对应于每个更高的胶囊。为了解决这个限制，我们用两个分支来近似路由过程：一个主分支，它从下层的直接接触中收集主要信息;一个辅助分支，根据在其他下层胶囊中编码的模式变量补充master。与先前的迭代和无监督路由方案相比，这两个分支以快速，监督和一次性通过方式进行通信。因此，模型的复杂性和运行时间大幅减少。通过路由以使更高的胶囊与下胶囊具有一致性，我们扩展该机制以补偿附近层中信息的快速丢失。我们设计了一个反馈协议单元，以发回更高的胶囊作为反馈。它可以被视为对网络的额外正规化。通过比较两个分布（较低和较高胶囊）之间的最佳传输差异来实现反馈协议。这样的附加组件在胶囊和香草网络中都获得了一致的收益。我们提出的EncapNet在CIFAR10 / 100，SVHN和ImageNet的一个子集上的表现优于先前的最新技术。

##### URL
[http://arxiv.org/abs/1808.03749](http://arxiv.org/abs/1808.03749)

##### PDF
[http://arxiv.org/pdf/1808.03749](http://arxiv.org/pdf/1808.03749)

