---
layout: post
title: "Reinforced Evolutionary Neural Architecture Search"
date: 2019-04-10 11:12:02
categories: arXiv_CV
tags: arXiv_CV Segmentation NAS Semantic_Segmentation
author: Yukang Chen, Gaofeng Meng, Qian Zhang, Shiming Xiang, Chang Huang, Lisen Mu, Xinggang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search (NAS) is an important yet challenging task in network design due to its high computational consumption. To address this issue, we propose the Reinforced Evolutionary Neural Architecture Search (RE- NAS), which is an evolutionary method with the reinforced mutation for NAS. Our method integrates reinforced mutation into an evolution algorithm for neural architecture exploration, in which a mutation controller is introduced to learn the effects of slight modifications and make mutation actions. The reinforced mutation controller guides the model population to evolve efficiently. Furthermore, as child models can inherit parameters from their parents during evolution, our method requires very limited computational resources. In experiments, we conduct the proposed search method on CIFAR-10 and obtain a powerful network architecture, RENASNet. This architecture achieves a competitive result on CIFAR-10. The explored network architecture is transferable to ImageNet and achieves a new state-of-the-art accuracy, i.e., 75.7% top-1 accuracy with 5.36M parameters on mobile ImageNet. We further test its performance on semantic segmentation with DeepLabv3 on the PASCAL VOC. RENASNet outperforms MobileNet-v1, MobileNet-v2 and NASNet. It achieves 75.83% mIOU without being pre-trained on COCO.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.00193](https://arxiv.org/abs/1808.00193)

##### PDF
[https://arxiv.org/pdf/1808.00193](https://arxiv.org/pdf/1808.00193)

