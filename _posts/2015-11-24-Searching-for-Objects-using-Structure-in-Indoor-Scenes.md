---
layout: post
title: "Searching for Objects using Structure in Indoor Scenes"
date: 2015-11-24 14:05:28
categories: arXiv_CV
tags: arXiv_CV
author: Varun K. Nagaraja, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
To identify the location of objects of a particular class, a passive computer vision system generally processes all the regions in an image to finally output few regions. However, we can use structure in the scene to search for objects without processing the entire image. We propose a search technique that sequentially processes image regions such that the regions that are more likely to correspond to the query class object are explored earlier. We frame the problem as a Markov decision process and use an imitation learning algorithm to learn a search strategy. Since structure in the scene is essential for search, we work with indoor scene images as they contain both unary scene context information and object-object context in the scene. We perform experiments on the NYU-depth v2 dataset and show that the unary scene context features alone can achieve a significantly high average precision while processing only 20-25\% of the regions for classes like bed and sofa. By considering object-object context along with the scene context features, the performance is further improved for classes like counter, lamp, pillow and sofa.

##### Abstract (translated by Google)
为了识别特定类别的对象的位置，被动计算机视觉系统通常处理图像中的所有区域以最终输出少量区域。但是，我们可以使用场景中的结构来搜索对象而不处理整个图像。我们提出了一种搜索技术，该技术按顺序处理图像区域，以便更早地探索更可能对应于查询类对象的区域。我们把这个问题作为一个马尔可夫决策过程来构建，并使用一个模仿学习算法来学习一个搜索策略。由于场景中的结构对于搜索至关重要，因此我们使用室内场景图像，因为它们包含场景中的一元场景上下文信息和对象对象上下文。我们在NYU深度v2数据集上进行实验，结果表明单独的一元场景上下文特征可以达到很高的平均精确度，同时仅处理床和沙发类的20-25％的区域。通过考虑对象对象上下文以及场景上下文特征，诸如柜台，灯，枕头和沙发等类别的表现进一步改善。

##### URL
[https://arxiv.org/abs/1511.07710](https://arxiv.org/abs/1511.07710)

##### PDF
[https://arxiv.org/pdf/1511.07710](https://arxiv.org/pdf/1511.07710)

