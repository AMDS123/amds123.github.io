---
layout: post
title: "Is Robustness the Cost of Accuracy? -- A Comprehensive Study on the Robustness of 18 Deep Image Classification Models"
date: 2018-08-05 21:43:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Classification Prediction
author: Dong Su, Huan Zhang, Hongge Chen, Jinfeng Yi, Pin-Yu Chen, Yupeng Gao
mathjax: true
---

* content
{:toc}

##### Abstract
The prediction accuracy has been the long-lasting and sole standard for comparing the performance of different image classification models, including the ImageNet competition. However, recent studies have highlighted the lack of robustness in well-trained deep neural networks to adversarial examples. Visually imperceptible perturbations to natural images can easily be crafted and mislead the image classifiers towards misclassification. To demystify the trade-offs between robustness and accuracy, in this paper we thoroughly benchmark 18 ImageNet models using multiple robustness metrics, including the distortion, success rate and transferability of adversarial examples between 306 pairs of models. Our extensive experimental results reveal several new insights: (1) linear scaling law - the empirical $\ell_2$ and $\ell_\infty$ distortion metrics scale linearly with the logarithm of classification error; (2) model architecture is a more critical factor to robustness than model size, and the disclosed accuracy-robustness Pareto frontier can be used as an evaluation criterion for ImageNet model designers; (3) for a similar network architecture, increasing network depth slightly improves robustness in $\ell_\infty$ distortion; (4) there exist models (in VGG family) that exhibit high adversarial transferability, while most adversarial examples crafted from one model can only be transferred within the same family. Experiment code is publicly available at \url{this https URL}.

##### Abstract (translated by Google)
预测准确性是比较不同图像分类模型（包括ImageNet竞争）的性能的持久和唯一标准。然而，最近的研究强调了训练有素的深度神经网络对对抗性例子缺乏鲁棒性。对自然图像的视觉上难以察觉的扰动可以容易地制作并且误导图像分类器以进行错误分类。为了揭示鲁棒性和准确性之间的权衡，在本文中，我们使用多个稳健性度量标准对18个ImageNet模型进行了彻底的基准测试，包括306对模型之间的对抗性示例的失真，成功率和可转移性。我们广泛的实验结果揭示了几个新的见解：（1）线性标度法 - 经验$ \ ell_2 $和$ \ ell_ \ infty $失真度量与分类错误的对数线性对比; （2）模型体系结构是一个比模型大小更具有鲁棒性的关键因素，所公开的精度 - 鲁棒性Pareto前沿可以作为ImageNet模型设计者的评估标准; （3）对于类似的网络架构，增加网络深度会略微提高$ \ ell_ \ infty $失真的鲁棒性; （4）存在具有高对抗性可转移性的模型（在VGG族中），而从一个模型制作的大多数对抗性实例只能在同一族中转移。实验代码可在\ url {此https网址}公开获取。

##### URL
[https://arxiv.org/abs/1808.01688](https://arxiv.org/abs/1808.01688)

##### PDF
[https://arxiv.org/pdf/1808.01688](https://arxiv.org/pdf/1808.01688)

