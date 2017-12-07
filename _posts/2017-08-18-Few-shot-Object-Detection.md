---
layout: post
title: "Few-shot Object Detection"
date: 2017-08-18 07:07:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xuanyi Dong, Liang Zheng, Fan Ma, Yi Yang, Deyu Meng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study object detection using a large pool of unlabeled images and only a few labeled images per category, named "few-shot object detection". The key challenge consists in generating trustworthy training samples as many as possible from the pool. Using few training examples as seeds, our method iterates between model training and high-confidence sample selection. In training, easy samples are generated first and, then the poorly initialized model undergoes improvement. As the model becomes more discriminative, challenging but reliable samples are selected. After that, another round of model improvement takes place. To further improve the precision and recall of the generated training samples, we embed multiple detection models in our framework, which has proven to outperform the single model baseline and the model ensemble method. Experiments on PASCAL VOC'07 indicate that by using as few as three or four samples selected for each category, our method produces very competitive results when compared to the state-of-the-art weakly-supervised approaches using a large number of image-level labels.

##### Abstract (translated by Google)
在本文中，我们使用大量未标记的图像来研究对象检测，并且每个类别只有少数标记的图像，被称为“少量对象检测”。关键的挑战在于尽可能多地从池中生成可信的培训样本。以少数训练样本作为种子，我们的方法在模型训练和高置信度样本选择之间进行迭代。在训练中，首先生成简单的样本，然后初始化较差的模型进行改进。随着模型变得更具有判别力，选择具有挑战性但可靠的样本。之后，又进行了一轮模型改进。为了进一步提高生成的训练样本的精度和查全率，我们将多个检测模型嵌入到我们的框架中，这已经被证明优于单个模型基线和模型集成方法。对PASCAL VOC'07的实验表明，通过使用为每个类别选择的少至三或四个样本，我们的方法与使用大量图像处理技术的现有技术的弱监督方法相比产生非常有竞争力的结果，级别的标签。

##### URL
[https://arxiv.org/abs/1706.08249](https://arxiv.org/abs/1706.08249)

##### PDF
[https://arxiv.org/pdf/1706.08249](https://arxiv.org/pdf/1706.08249)

