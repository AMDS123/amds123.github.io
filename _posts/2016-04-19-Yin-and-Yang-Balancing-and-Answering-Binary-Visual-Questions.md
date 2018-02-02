---
layout: post
title: "Yin and Yang: Balancing and Answering Binary Visual Questions"
date: 2016-04-19 19:30:00
categories: arXiv_CV
tags: arXiv_CV QA VQA Recognition
author: Peng Zhang, Yash Goyal, Douglas Summers-Stay, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
The complex compositional structure of language makes problems at the intersection of vision and language challenging. But language also provides a strong prior that can result in good superficial performance, without the underlying models truly understanding the visual content. This can hinder progress in pushing state of art in the computer vision aspects of multi-modal AI. In this paper, we address binary Visual Question Answering (VQA) on abstract scenes. We formulate this problem as visual verification of concepts inquired in the questions. Specifically, we convert the question to a tuple that concisely summarizes the visual concept to be detected in the image. If the concept can be found in the image, the answer to the question is "yes", and otherwise "no". Abstract scenes play two roles (1) They allow us to focus on the high-level semantics of the VQA task as opposed to the low-level recognition problems, and perhaps more importantly, (2) They provide us the modality to balance the dataset such that language priors are controlled, and the role of vision is essential. In particular, we collect fine-grained pairs of scenes for every question, such that the answer to the question is "yes" for one scene, and "no" for the other for the exact same question. Indeed, language priors alone do not perform better than chance on our balanced dataset. Moreover, our proposed approach matches the performance of a state-of-the-art VQA approach on the unbalanced dataset, and outperforms it on the balanced dataset.

##### Abstract (translated by Google)
语言的复杂构成结构使得在视觉和语言的交叉点处有问题。但是语言也提供了一个强大的优先事项，可以产生很好的表面效果，而不需要底层模型真正理解视觉内容。这可能会阻碍在多模态AI的计算机视觉方面推进艺术进步。在本文中，我们解决抽象场景中的二进制视觉问题回答（VQA）。我们把这个问题制定成问题中查询概念的可视化验证。具体来说，我们把这个问题转换成一个元组，简单地概括了图像中要被检测到的视觉概念。如果这个概念可以在图像中找到，问题的答案是“是”，否则“否”。抽象场景扮演两个角色（1）它们使我们能够专注于VQA任务的高级语义而不是低级别的识别问题，更重要的是，（2）它们为我们提供了平衡数据集的方式这样语言的先驱就受到控制，而视觉的作用也是必不可少的。特别是，我们为每个问题收集精细的场景对，一个场景的问题答案是“是”，另一个问题的答案是“否”。事实上，语言先验本身在我们平衡的数据集上的表现并不比单纯的好。此外，我们提出的方法匹配最先进的VQA方法在不平衡数据集上的性能，并且在平衡数据集上胜过它。

##### URL
[https://arxiv.org/abs/1511.05099](https://arxiv.org/abs/1511.05099)

##### PDF
[https://arxiv.org/pdf/1511.05099](https://arxiv.org/pdf/1511.05099)

