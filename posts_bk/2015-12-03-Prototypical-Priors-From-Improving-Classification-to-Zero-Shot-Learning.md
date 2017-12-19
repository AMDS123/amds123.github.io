---
layout: post
title: "Prototypical Priors: From Improving Classification to Zero-Shot Learning"
date: 2015-12-03 19:06:16
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Inference Classification Deep_Learning Relation Recognition
author: Saumya Jetley, Bernardino Romera-Paredes, Sadeep Jayasumana, Philip Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works on zero-shot learning make use of side information such as visual attributes or natural language semantics to define the relations between output visual classes and then use these relationships to draw inference on new unseen classes at test time. In a novel extension to this idea, we propose the use of visual prototypical concepts as side information. For most real-world visual object categories, it may be difficult to establish a unique prototype. However, in cases such as traffic signs, brand logos, flags, and even natural language characters, these prototypical templates are available and can be leveraged for an improved recognition performance. The present work proposes a way to incorporate this prototypical information in a deep learning framework. Using prototypes as prior information, the deepnet pipeline learns the input image projections into the prototypical embedding space subject to minimization of the final classification loss. Based on our experiments with two different datasets of traffic signs and brand logos, prototypical embeddings incorporated in a conventional convolutional neural network improve the recognition performance. Recognition accuracy on the Belga logo dataset is especially noteworthy and establishes a new state-of-the-art. In zero-shot learning scenarios, the same system can be directly deployed to draw inference on unseen classes by simply adding the prototypical information for these new classes at test time. Thus, unlike earlier approaches, testing on seen and unseen classes is handled using the same pipeline, and the system can be tuned for a trade-off of seen and unseen class performance as per task requirement. Comparison with one of the latest works in the zero-shot learning domain yields top results on the two datasets mentioned above.

##### Abstract (translated by Google)
最近有关零点学习的研究利用视觉属性或自然语言语义等边信息来定义输出视觉类之间的关系，然后利用这些关系在测试时间对新的看不见的类进行推理。在这个想法的一个新颖的扩展中，我们提出使用视觉原型概念作为辅助信息。对于大多数真实世界的视觉对象类别，可能难以建立独特的原型。但是，在交通标志，品牌徽标，标志甚至自然语言字符等情况下，这些原型模板都可用，并且可以用于提高识别性能。目前的工作提出了一种将这种原型信息纳入深度学习框架的方法。使用原型作为先验信息，深网管道将输入图像投影学习到原型嵌入空间中，以最小化最终分类损失。基于我们对两种不同的交通标志和品牌标志的数据集的实验，在常规的卷积神经网络中包含的原型嵌入提高了识别性能。 Belga标识数据集的识别准确性尤为值得关注，并建立了一个新的技术水平。在零点学习场景中，可以直接部署同一个系统，通过简单地在测试时间添加这些新类的原型信息来对看不见的类进行推理。因此，与早期的方法不同，对于看到和看不见的类的测试使用相同的流水线进行处理，并且系统可以根据任务需求进行调整，以对所看到和看不见的课程表现进行权衡。与零点学习领域的最新作品之一进行比较，得出了上述两个数据集的最佳结果。

##### URL
[https://arxiv.org/abs/1512.01192](https://arxiv.org/abs/1512.01192)

##### PDF
[https://arxiv.org/pdf/1512.01192](https://arxiv.org/pdf/1512.01192)

