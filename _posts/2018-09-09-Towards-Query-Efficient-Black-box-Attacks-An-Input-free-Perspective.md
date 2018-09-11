---
layout: post
title: "Towards Query Efficient Black-box Attacks: An Input-free Perspective"
date: 2018-09-09 03:49:06
categories: arXiv_CV
tags: arXiv_CV Adversarial Detection
author: Yali Du, Meng Fang, Jinfeng Yi, Jun Cheng, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have highlighted that deep neural networks (DNNs) are vulnerable to adversarial attacks, even in a black-box scenario. However, most of the existing black-box attack algorithms need to make a huge amount of queries to perform attacks, which is not practical in the real world. We note one of the main reasons for the massive queries is that the adversarial example is required to be visually similar to the original image, but in many cases, how adversarial examples look like does not matter much. It inspires us to introduce a new attack called \emph{input-free} attack, under which an adversary can choose an arbitrary image to start with and is allowed to add perceptible perturbations on it. Following this approach, we propose two techniques to significantly reduce the query complexity. First, we initialize an adversarial example with a gray color image on which every pixel has roughly the same importance for the target model. Then we shrink the dimension of the attack space by perturbing a small region and tiling it to cover the input image. To make our algorithm more effective, we stabilize a projected gradient ascent algorithm with momentum, and also propose a heuristic approach for region size selection. Through extensive experiments, we show that with only 1,701 queries on average, we can perturb a gray image to any target class of ImageNet with a 100\% success rate on InceptionV3. Besides, our algorithm has successfully defeated two real-world systems, the Clarifai food detection API and the Baidu Animal Identification API.

##### Abstract (translated by Google)
最近的研究强调，深度神经网络（DNN）很容易受到对抗性攻击，即使在黑盒子情况下也是如此。但是，大多数现有的黑盒攻击算法需要进行大量的查询来执行攻击，这在现实世界中是不实际的。我们注意到大量查询的主要原因之一是对抗性示例需要在视觉上与原始图像类似，但在许多情况下，对抗性示例的外观并不重要。它激励我们引入一种名为\ emph {input-free}攻击的新攻击，在该攻击下，攻击者可以选择任意图像开始，并允许在其上添加可察觉的扰动。遵循这种方法，我们提出了两种技术来显着降低查询复杂性。首先，我们使用灰色图像初始化对抗性示例，其中每个像素对目标模型具有大致相同的重要性。然后我们通过扰动一个小区域并将其平铺以覆盖输入图像来缩小攻击空间的维度。为了使我们的算法更有效，我们稳定了具有动量的投影梯度上升算法，并且还提出了用于区域大小选择的启发式方法。通过大量实验，我们发现平均只有1,701个查询，我们可以将灰色图像扰乱到ImageNet的任何目标类，在InceptionV3上成功率为100％。此外，我们的算法已经成功击败了两个真实世界的系统，Clarifai食品检测API和百度动物识别API。

##### URL
[http://arxiv.org/abs/1809.02918](http://arxiv.org/abs/1809.02918)

##### PDF
[http://arxiv.org/pdf/1809.02918](http://arxiv.org/pdf/1809.02918)

