---
layout: post
title: "Exploring Human-like Attention Supervision in Visual Question Answering"
date: 2017-09-19 09:19:08
categories: arXiv_CV
tags: arXiv_CV VQA
author: Tingting Qiao, Jianfeng Dong, Duanqing Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanisms have been widely applied in the Visual Question Answering (VQA) task, as they help to focus on the area-of-interest of both visual and textual information. To answer the questions correctly, the model needs to selectively target different areas of an image, which suggests that an attention-based model may benefit from an explicit attention supervision. In this work, we aim to address the problem of adding attention supervision to VQA models. Since there is a lack of human attention data, we first propose a Human Attention Network (HAN) to generate human-like attention maps, training on a recently released dataset called Human ATtention Dataset (VQA-HAT). Then, we apply the pre-trained HAN on the VQA v2.0 dataset to automatically produce the human-like attention maps for all image-question pairs. The generated human-like attention map dataset for the VQA v2.0 dataset is named as Human-Like ATtention (HLAT) dataset. Finally, we apply human-like attention supervision to an attention-based VQA model. The experiments show that adding human-like supervision yields a more accurate attention together with a better performance, showing a promising future for human-like attention supervision in VQA.

##### Abstract (translated by Google)
注意机制已被广泛应用于视觉问答（VQA）任务中，因为它们有助于关注视觉和文本信息的兴趣区域。为了正确回答问题，模型需要选择性地针对图像的不同区域，这表明基于注意的模型可能受益于明确的注意力监督。在这项工作中，我们的目标是解决VQA模型增加注意力监督的问题。由于缺乏人类关注的数据，我们首先提出一个人类关注网络（HAN）来生成人类关注地图，在最近发布的一个名为人类关注数据集（VQA-HAT）的数据集上进行培训。然后，我们在VQA v2.0数据集上应用预先训练好的HAN，为所有图像问题对自动生成类似人的关注图。 VQA v2.0数据集生成的类人注意地图数据集被命名为类人力注意（Human-Like ATtention，HLAT）数据集。最后，我们将人类的注意力监督应用于注意力的VQA模型。实验结果表明，加入人性化监督能带来更为准确的关注和更好的表现，显示VQA中类人注意监督的前景看好。

##### URL
[https://arxiv.org/abs/1709.06308](https://arxiv.org/abs/1709.06308)

##### PDF
[https://arxiv.org/pdf/1709.06308](https://arxiv.org/pdf/1709.06308)

