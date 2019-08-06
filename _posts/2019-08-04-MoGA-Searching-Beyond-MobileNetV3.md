---
layout: post
title: "MoGA: Searching Beyond MobileNetV3"
date: 2019-08-04 10:40:04
categories: arXiv_CV
tags: arXiv_CV
author: Xiangxiang Chu, Bo Zhang, Ruijun Xu
mathjax: true
---

* content
{:toc}

##### Abstract
The evolution of MobileNets has laid a solid foundation for neural network application on the mobile end. With the latest MobileNetV3, neural architecture search again claimed its supremacy on network design. Till today all mobile methods mainly focus on CPU latency instead of GPU, the latter, however, has lower overhead and interference and is much preferred in the industry. To mitigate this gap, we propose the first Mobile GPU-Aware (MoGA) neural architecture search in order to be precisely tailored for real-world applications. Further, the ultimate objective to devise a mobile network lies in achieving better performance by maximizing the utilization of bounded resources. While urging higher capability and restraining time consumption, we unconventionally encourage increasing the number of parameters for higher representational power. Undoubtedly, these three forces are not reconcilable and we have to alleviate the tension by weighted evolution techniques. Lastly, we deliver our searched networks at a mobile scale that outperform MobileNetV3 under the similar latency constraints, i.e., MoGA-A achieves 75.9\% top-1 accuracy on ImageNet, MoGA-B meets 75.5\% which costs only 0.5ms more on mobile GPU than MobileNetV3, which scores 75.2\%. MoGA-C best attests GPU-awareness by reaching 75.3\% and being slower on CPU but faster on GPU. The models and test code is made available here https://github.com/xiaomi-automl/MoGA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01314](http://arxiv.org/abs/1908.01314)

##### PDF
[http://arxiv.org/pdf/1908.01314](http://arxiv.org/pdf/1908.01314)

