---
layout: post
title: "Terabyte-scale Deep Multiple Instance Learning for Classification and Localization in Pathology"
date: 2018-05-17 22:43:46
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Prediction
author: Gabriele Campanella, Vitor Werneck Krauss Silva, Thomas J. Fuchs
mathjax: true
---

* content
{:toc}

##### Abstract
In the field of computational pathology, the use of decision support systems powered by state-of-the-art deep learning solutions has been hampered by the lack of large labeled datasets. Until recently, studies relied on datasets in the order of few hundreds of slides which are not enough to train a model that can work at scale in the clinic. Here, we have gathered a dataset consisting of 12,160 slides, two orders of magnitude larger than previous datasets in pathology and equivalent to 25 times the pixel count of the entire ImageNet dataset. Given the size of our dataset it is possible for us to train a deep learning model under the Multiple Instance Learning (MIL) assumption where only the overall slide diagnosis is necessary for training, avoiding all the expensive pixel-wise annotations that are usually part of supervised learning approaches. We test our framework on a complex task, that of prostate cancer diagnosis on needle biopsies. We performed a thorough evaluation of the performance of our MIL pipeline under several conditions achieving an AUC of 0.98 on a held-out test set of 1,824 slides. These results open the way for training accurate diagnosis prediction models at scale, laying the foundation for decision support system deployment in the clinic.

##### Abstract (translated by Google)
在计算病理学领域，由于缺乏大型标记数据集，阻碍了采用最先进深度学习解决方案的决策支持系统。直到最近，研究都依赖于数百张幻灯片的数据集，这些数据集不足以训练可在诊所中大规模工作的模型。在这里，我们收集了包含12,160张幻灯片的数据集，比病理学先前的数据集大两个数量级，相当于整个ImageNet数据集的25倍像素数。考虑到我们的数据集的大小，我们有可能在多实例学习（MIL）假设下训练深度学习模型，其中只有整体幻灯片诊断对于训练是必需的，从而避免所有昂贵的基于像素的注释，这些注释通常是有监督的学习方法。我们在一项复杂的任务上测试我们的框架，那就是穿刺针活检诊断前列腺癌。在几个条件下，我们对MIL管道的性能进行了全面评估，在一个由1,824张幻灯片组成的测试集上实现了0.98的AUC。这些结果为大规模训练准确的诊断预测模型开辟了道路，奠定了诊所支持系统部署的基础。

##### URL
[http://arxiv.org/abs/1805.06983](http://arxiv.org/abs/1805.06983)

##### PDF
[http://arxiv.org/pdf/1805.06983](http://arxiv.org/pdf/1805.06983)

