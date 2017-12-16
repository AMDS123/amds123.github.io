---
layout: post
title: "Knowledge Guided Disambiguation for Large-Scale Scene Classification with Multi-Resolution CNNs"
date: 2017-02-21 21:00:55
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Recognition
author: Limin Wang, Sheng Guo, Weilin Huang, Yuanjun Xiong, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have made remarkable progress on scene recognition, partially due to these recent large-scale scene datasets, such as the Places and Places2. Scene categories are often defined by multi-level information, including local objects, global layout, and background environment, thus leading to large intra-class variations. In addition, with the increasing number of scene categories, label ambiguity has become another crucial issue in large-scale classification. This paper focuses on large-scale scene recognition and makes two major contributions to tackle these issues. First, we propose a multi-resolution CNN architecture that captures visual content and structure at multiple levels. The multi-resolution CNNs are composed of coarse resolution CNNs and fine resolution CNNs, which are complementary to each other. Second, we design two knowledge guided disambiguation techniques to deal with the problem of label ambiguity. (i) We exploit the knowledge from the confusion matrix computed on validation data to merge ambiguous classes into a super category. (ii) We utilize the knowledge of extra networks to produce a soft label for each image. Then the super categories or soft labels are employed to guide CNN training on the Places2. We conduct extensive experiments on three large-scale image datasets (ImageNet, Places, and Places2), demonstrating the effectiveness of our approach. Furthermore, our method takes part in two major scene recognition challenges, and achieves the second place at the Places2 challenge in ILSVRC 2015, and the first place at the LSUN challenge in CVPR 2016. Finally, we directly test the learned representations on other scene benchmarks, and obtain the new state-of-the-art results on the MIT Indoor67 (86.7\%) and SUN397 (72.0\%). We release the code and models at~\url{this https URL}.

##### Abstract (translated by Google)
卷积神经网络（CNNs）在场景识别方面取得了令人瞩目的成就，部分原因在于最近的大规模场景数据集，比如场所和场所2。场景类别往往由多层次的信息来定义，包括局部对象，全局布局，背景环境，从而导致类内变化较大。另外，随着场景类别数量的增加，标签模糊也成为大规模分类的另一个关键问题。本文着重于大规模的场景识别，并为解决这些问题做出了两大贡献。首先，我们提出了一个多分辨率的CNN架构，可以在多个层面捕捉视觉内容和结构。多分辨率CNN由粗分辨率CNN和高分辨率CNN组成，互为补充。其次，设计了两种知识导向的消歧技术来处理标签模糊的问题。 （i）我们利用验证数据上计算的混淆矩阵中的知识将不明确的类合并为超类。 （ii）我们利用额外网络的知识为每个图像生成一个软标签。然后使用超级类别或软标签来指导Places2上的CNN培训。我们对三个大型图像数据集（ImageNet，Places和Places2）进行了广泛的实验，证明了我们的方法的有效性。此外，我们的方法还参与了两个主要的场景识别挑战，在2015年ILSVRC的Places2挑战赛中获得第二名，在2016年CVPR挑战赛中获得第一名。最后，我们直接测试其他场景基准并获得MIT Indoor67（86.7％）和SUN397（72.0％）的最新成果。我们在〜\ url {this https URL}上发布代码和模型。

##### URL
[https://arxiv.org/abs/1610.01119](https://arxiv.org/abs/1610.01119)

##### PDF
[https://arxiv.org/pdf/1610.01119](https://arxiv.org/pdf/1610.01119)

