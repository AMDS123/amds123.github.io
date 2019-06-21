---
layout: post
title: "SwiftNet: Using Graph Propagation as Meta-knowledge to Search HighlyvRepresentative Neural Architectures"
date: 2019-06-19 19:00:12
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference
author: Hsin-Pai (Dave) Cheng, Tunhou Zhang, Yukun Yang, Feng Yan, Shiyu Li, Harris Teague, Hai (Helen)Li, Yiran Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Designing neural architectures for edge devices is subject to constraints of accuracy, inference latency, and computational cost. Traditionally, researchers manually craft deep neural networks to meet the needs of mobile devices. Neural Architecture Search (NAS) was proposed to automate the neural architecture design without requiring extensive domain expertise and significant manual efforts. Recent works utilized NAS to design mobile models by taking into account hardware constraints and achieved state-of-the-art accuracy with fewer parameters and less computational cost measured in Multiply-accumulates (MACs). To find highly compact neural architectures, existing works relies on predefined cells and directly applying width multiplier, which may potentially limit the model flexibility, reduce the useful feature map information, and cause accuracy drop. To conquer this issue, we propose GRAM(GRAph propagation as Meta-knowledge) that adopts fine-grained (node-wise) search method and accumulates the knowledge learned in updates into a meta-graph. As a result, GRAM can enable more flexible search space and achieve higher search efficiency. Without the constraints of predefined cell or blocks, we propose a new structure-level pruning method to remove redundant operations in neural architectures. SwiftNet, which is a set of models discovered by GRAM, outperforms MobileNet-V2 by 2.15x higher accuracy density and 2.42x faster with similar accuracy. Compared with FBNet, SwiftNet reduces the search cost by 26x and achieves 2.35x higher accuracy density and 1.47x speedup while preserving similar accuracy. SwiftNetcan obtain 63.28% top-1 accuracy on ImageNet-1K with only 53M MACs and 2.07M parameters. The corresponding inference latency is only 19.09 ms on Google Pixel 1.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08305](http://arxiv.org/abs/1906.08305)

##### PDF
[http://arxiv.org/pdf/1906.08305](http://arxiv.org/pdf/1906.08305)

