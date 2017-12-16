---
layout: post
title: "Weakly Supervised Object Localization Using Things and Stuff Transfer"
date: 2017-08-07 14:00:41
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Weakly_Supervised Relation
author: Miaojing Shi, Holger Caesar, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to help weakly supervised object localization for classes where location annotations are not available, by transferring things and stuff knowledge from a source set with available annotations. The source and target classes might share similar appearance (e.g. bear fur is similar to cat fur) or appear against similar background (e.g. horse and sheep appear against grass). To exploit this, we acquire three types of knowledge from the source set: a segmentation model trained on both thing and stuff classes; similarity relations between target and source classes; and co-occurrence relations between thing and stuff classes in the source. The segmentation model is used to generate thing and stuff segmentation maps on a target image, while the class similarity and co-occurrence knowledge help refining them. We then incorporate these maps as new cues into a multiple instance learning framework (MIL), propagating the transferred knowledge from the pixel level to the object proposal level. In extensive experiments, we conduct our transfer from the PASCAL Context dataset (source) to the ILSVRC, COCO and PASCAL VOC 2007 datasets (targets). We evaluate our transfer across widely different thing classes, including some that are not similar in appearance, but appear against similar background. The results demonstrate significant improvement over standard MIL, and we outperform the state-of-the-art in the transfer setting.

##### Abstract (translated by Google)
我们建议通过使用可用的注释从源集合中转移事物和东西来帮助对没有位置注释的类进行弱监督的对象本地化。源类和目标类可能具有相似的外观（例如，熊的毛皮类似于猫的毛皮）或者出现在相似的背景下（例如，马和绵羊对着草地出现）。为了利用这一点，我们从源集合中获得三种类型的知识：一种在事物和东西类别上训练的分割模型;目标类与源类的相似关系;以及事物与东西类之间的同现关系。分割模型用于在目标图像上生成事物和东西分割图，而类相似性和共生知识有助于提炼它们。然后，我们将这些地图作为新的线索并入多实例学习框架（MIL），将传递的知识从像素级传播到对象提议级。在广泛的实验中，我们从PASCAL上下文数据集（源）转换到ILSVRC，COCO和PASCAL VOC 2007数据集（目标）。我们评估我们在广泛不同的事物类别中的转移，包括一些在外观上不相似，但出现在类似的背景。结果证明，与标准MIL相比，其性能有显着的提高，而且我们在传输设置上超越了最先进的技术水平。

##### URL
[https://arxiv.org/abs/1703.08000](https://arxiv.org/abs/1703.08000)

##### PDF
[https://arxiv.org/pdf/1703.08000](https://arxiv.org/pdf/1703.08000)

