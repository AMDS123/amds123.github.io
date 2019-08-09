---
layout: post
title: "Attend To Count: Crowd Counting with Adaptive Capacity Multi-scale CNNs"
date: 2019-08-07 18:57:35
categories: arXiv_CV
tags: arXiv_CV Attention GAN CNN
author: Zhikang Zou, Yu Cheng, Xiaoye Qu, Shouling Ji, Xiaoxiao Guo, Pan Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting is a challenging task due to the large variations in crowd distributions. Previous methods tend to tackle the whole image with a single fixed structure, which is unable to handle diverse complicated scenes with different crowd densities. Hence, we propose the Adaptive Capacity Multi-scale convolutional neural networks (ACM-CNN), a novel crowd counting approach which can assign different capacities to different portions of the input. The intuition is that the model should focus on important regions of the input image and optimize its capacity allocation conditioning on the crowd intensive degree. ACM-CNN consists of three types of modules: a coarse network, a fine network, and a smooth network. The coarse network is used to explore the areas that need to be focused via count attention mechanism, and generate a rough feature map. Then the fine network processes the areas of interest into a fine feature map. To alleviate the sense of division caused by fusion, the smooth network is designed to combine two feature maps organically to produce high-quality density maps. Extensive experiments are conducted on five mainstream datasets. The results demonstrate the effectiveness of the proposed model for both density estimation and crowd counting tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02797](http://arxiv.org/abs/1908.02797)

##### PDF
[http://arxiv.org/pdf/1908.02797](http://arxiv.org/pdf/1908.02797)

