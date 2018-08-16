---
layout: post
title: "Few-Example Object Detection with Model Communication"
date: 2018-08-15 01:25:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xuanyi Dong, Liang Zheng, Fan Ma, Yi Yang, Deyu Meng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study object detection using a large pool of unlabeled images and only a few labeled images per category, named "few-example object detection". The key challenge consists in generating trustworthy training samples as many as possible from the pool. Using few training examples as seeds, our method iterates between model training and high-confidence sample selection. In training, easy samples are generated first and, then the poorly initialized model undergoes improvement. As the model becomes more discriminative, challenging but reliable samples are selected. After that, another round of model improvement takes place. To further improve the precision and recall of the generated training samples, we embed multiple detection models in our framework, which has proven to outperform the single model baseline and the model ensemble method. Experiments on PASCAL VOC'07, MS COCO'14, and ILSVRC'13 indicate that by using as few as three or four samples selected for each category, our method produces very competitive results when compared to the state-of-the-art weakly-supervised approaches using a large number of image-level labels.

##### Abstract (translated by Google)
在本文中，我们使用大量未标记图像和每个类别只有少量标记图像来研究对象检测，命名为“少量示例对象检测”。关键的挑战在于尽可能多地从池中生成值得信赖的培训样本。使用少量训练样例作为种子，我们的方法在模型训练和高可信度样本选择之间进行迭代。在训练中，首先生成简单的样本，然后对初始化不良的模型进行改进。随着模型变得更具辨别力，选择具有挑战性但可靠的样本。之后，又进行了另一轮模型改进。为了进一步提高生成的训练样本的精度和召回率，我们在我们的框架中嵌入了多个检测模型，已经证明其优于单一模型基线和模型集合方法。 PASCAL VOC'07，MS COCO'14和ILSVRC'13的实验表明，通过使用为每个类别选择的少至三个或四个样本，我们的方法与最先进的弱技术相比产生非常有竞争力的结果 - 使用大量图像级标签的监督方法。

##### URL
[http://arxiv.org/abs/1706.08249](http://arxiv.org/abs/1706.08249)

##### PDF
[http://arxiv.org/pdf/1706.08249](http://arxiv.org/pdf/1706.08249)

