---
layout: post
title: "Generating Triples with Adversarial Networks for Scene Graph Construction"
date: 2018-02-07 19:12:31
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Object_Detection Attention GAN Caption Image_Classification Classification Deep_Learning Detection Relation VQA
author: Matthew Klawonn, Eric Heim
mathjax: true
---

* content
{:toc}

##### Abstract
Driven by successes in deep learning, computer vision research has begun to move beyond object detection and image classification to more sophisticated tasks like image captioning or visual question answering. Motivating such endeavors is the desire for models to capture not only objects present in an image, but more fine-grained aspects of a scene such as relationships between objects and their attributes. Scene graphs provide a formal construct for capturing these aspects of an image. Despite this, there have been only a few recent efforts to generate scene graphs from imagery. Previous works limit themselves to settings where bounding box information is available at train time and do not attempt to generate scene graphs with attributes. In this paper we propose a method, based on recent advancements in Generative Adversarial Networks, to overcome these deficiencies. We take the approach of first generating small subgraphs, each describing a single statement about a scene from a specific region of the input image chosen using an attention mechanism. By doing so, our method is able to produce portions of the scene graphs with attribute information without the need for bounding box labels. Then, the complete scene graph is constructed from these subgraphs. We show that our model improves upon prior work in scene graph generation on state-of-the-art data sets and accepted metrics. Further, we demonstrate that our model is capable of handling a larger vocabulary size than prior work has attempted.

##### Abstract (translated by Google)
在深度学习的成功驱动下，计算机视觉研究已经开始超越对象检测和图像分类，转向更复杂的任务，如图像字幕或视觉问答。激发这种努力的是模型不仅要捕获图像中存在的对象，还要捕获场景中更精细的方面，例如对象与其属性之间的关系。场景图提供了用于捕获图像的这些方面的正式构造。尽管如此，最近只有一些努力从图像生成场景图。以前的工作仅限于在列车时可获得边界框信息的设置，并且不会尝试生成具有属性的场景图。在本文中，我们提出了一种基于生成对抗网络的最新进展的方法，以克服这些缺陷。我们采用首先生成小子图的方法，每个子图描述关于使用注意机制选择的输入图像的特定区域的场景的单个陈述。通过这样做，我们的方法能够生成具有属性信息的部分场景图，而不需要边界框标签。然后，从这些子图构建完整的场景图。我们展示了我们的模型改进了先前在最先进数据集和已接受度量上生成场景图的工作。此外，我们证明我们的模型能够处理比以前的工作更大的词汇量。

##### URL
[https://arxiv.org/abs/1802.02598](https://arxiv.org/abs/1802.02598)

##### PDF
[https://arxiv.org/pdf/1802.02598](https://arxiv.org/pdf/1802.02598)

