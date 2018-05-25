---
layout: post
title: "R-VQA: Learning Visual Relation Facts with Semantic Attention for Visual Question Answering"
date: 2018-05-24 14:43:30
categories: arXiv_AI
tags: arXiv_AI Object_Detection Knowledge QA Attention Embedding Detection Relation VQA
author: Pan Lu, Lei Ji, Wei Zhang, Nan Duan, Ming Zhou, Jianyong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Visual Question Answering (VQA) has emerged as one of the most significant tasks in multimodal learning as it requires understanding both visual and textual modalities. Existing methods mainly rely on extracting image and question features to learn their joint feature embedding via multimodal fusion or attention mechanism. Some recent studies utilize external VQA-independent models to detect candidate entities or attributes in images, which serve as semantic knowledge complementary to the VQA task. However, these candidate entities or attributes might be unrelated to the VQA task and have limited semantic capacities. To better utilize semantic knowledge in images, we propose a novel framework to learn visual relation facts for VQA. Specifically, we build up a Relation-VQA (R-VQA) dataset based on the Visual Genome dataset via a semantic similarity module, in which each data consists of an image, a corresponding question, a correct answer and a supporting relation fact. A well-defined relation detector is then adopted to predict visual question-related relation facts. We further propose a multi-step attention model composed of visual attention and semantic attention sequentially to extract related visual knowledge and semantic knowledge. We conduct comprehensive experiments on the two benchmark datasets, demonstrating that our model achieves state-of-the-art performance and verifying the benefit of considering visual relation facts.

##### Abstract (translated by Google)
最近，视觉问答（VQA）已经成为多模式学习中最重要的任务之一，因为它需要理解视觉和文本方式。现有的方法主要依靠提取图像和问题特征，通过多模态融合或关注机制来学习它们的联合特征嵌入。一些最近的研究利用外部VQA独立模型来检测图像中的候选实体或属性，其作为与VQA任务互补的语义知识。然而，这些候选实体或属性可能与VQA任务无关，并且语义能力有限。为了更好地利用图像中的语义知识，我们提出了一个新的框架来学习VQA的视觉关系事实。具体而言，我们通过语义相似度模块构建基于Visual Genome数据集的Relation-VQA（R-VQA）数据集，其中每个数据由图像，相应问题，正确答案和支持关系事实组成。然后采用明确的关系检测器来预测与视觉问题有关的关系事实。我们进一步提出了一种由视觉注意和语义注意组成的多步注意模型，以提取相关的视觉知识和语义知识。我们对这两个基准数据集进行了全面的实验，证明我们的模型达到了最先进的性能，并验证了考虑视觉关系事实的好处。

##### URL
[http://arxiv.org/abs/1805.09701](http://arxiv.org/abs/1805.09701)

##### PDF
[http://arxiv.org/pdf/1805.09701](http://arxiv.org/pdf/1805.09701)

