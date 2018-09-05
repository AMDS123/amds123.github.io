---
layout: post
title: "Learning to Navigate for Fine-grained Classification"
date: 2018-09-02 03:40:08
categories: arXiv_CV
tags: arXiv_CV Inference Classification Prediction
author: Ze Yang, Tiange Luo, Dong Wang, Zhiqiang Hu, Jun Gao, Liwei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained classification is challenging due to the difficulty of finding discriminative features. Finding those subtle traits that fully characterize the object is not straightforward. To handle this circumstance, we propose a novel self-supervision mechanism to effectively localize informative regions without the need of bounding-box/part annotations. Our model, termed NTS-Net for Navigator-Teacher-Scrutinizer Network, consists of a Navigator agent, a Teacher agent and a Scrutinizer agent. In consideration of intrinsic consistency between informativeness of the regions and their probability being ground-truth class, we design a novel training paradigm, which enables Navigator to detect most informative regions under the guidance from Teacher. After that, the Scrutinizer scrutinizes the proposed regions from Navigator and makes predictions. Our model can be viewed as a multi-agent cooperation, wherein agents benefit from each other, and make progress together. NTS-Net can be trained end-to-end, while provides accurate fine-grained classification predictions as well as highly informative regions during inference. We achieve state-of-the-art performance in extensive benchmark datasets.

##### Abstract (translated by Google)
由于难以找到辨别特征，细粒度分类具有挑战性。找到完全表征对象的那些微妙特征并不简单。为了处理这种情况，我们提出了一种新颖的自我监督机制，可以有效地定位信息区域而无需边界框/部分注释。我们的模型，称为Navigator-Teacher-Scrutinizer Network的NTS-Net，由Navigator代理，教师代理和Scrutinizer代理组成。考虑到地区信息量与地面真实性概率之间的内在一致性，我们设计了一种新颖的训练范式，使导航员能够在教师的指导下检测大部分信息区域。之后，Scrutinizer仔细检查Navigator中建议的区域并进行预测。我们的模型可以被视为一种多代理合作，其中代理商互相受益，共同进步。 NTS-Net可以端到端地进行训练，同时在推理期间提供准确的细粒度分类预测以及高信息区域。我们在广泛的基准数据集中实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1809.00287](http://arxiv.org/abs/1809.00287)

##### PDF
[http://arxiv.org/pdf/1809.00287](http://arxiv.org/pdf/1809.00287)

