---
layout: post
title: "Cross-type Biomedical Named Entity Recognition with Deep Multi-Task Learning"
date: 2018-01-30 04:44:14
categories: arXiv_CL
tags: arXiv_CL Knowledge Recognition
author: Xuan Wang, Yu Zhang, Xiang Ren, Yuhao Zhang, Marinka Zitnik, Jingbo Shang, Curtis Langlotz, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Motivation: Biomedical named entity recognition (BioNER) is the most fundamental task in biomedical text mining. State-of-the-art BioNER systems often require handcrafted features specifically designed for each type of biomedical entities. This feature generation process requires intensive labors from biomedical and linguistic experts, and makes it difficult to adapt these systems to new biomedical entity types. Although recent studies explored using neural network models for BioNER to free experts from manual feature generation, these models still require substantial human efforts to annotate massive training data. 
 Results: We propose a multi-task learning framework for BioNER that is based on neural network models to save human efforts. We build a global model by collectively training multiple models that share parameters, each model capturing the characteristics of a different biomedical entity type. In experiments on five BioNER benchmark datasets covering four major biomedical entity types, our model outperforms state-of-the-art systems and other neural network models by a large margin, even when only limited training data are available. Further analysis shows that the large performance gains come from sharing character- and word-level information between different biomedical entities. The approach creates new opportunities for text-mining approaches to help biomedical scientists better exploit knowledge in biomedical literature.

##### Abstract (translated by Google)
动机：生物医学命名实体识别（BioNER）是生物医学文本挖掘中最基本的任务。先进的BioNER系统通常需要专门为每种类型的生物医学实体设计的手工功能。这一特征生成过程需要来自生物医学和语言专家的大量劳动力，并且使这些系统适应新的生物医学实体类型变得困难。虽然最近的研究探索使用神经网络模型的BioNER从手动特征生成的专家，这些模型仍然需要大量的人力来注释大量的训练数据。
 结果：我们提出了一个基于神经网络模型的BioNER多任务学习框架，以节省人力。我们通过共同训练共享参数的多个模型来建立全球模型，每个模型捕捉不同生物医学实体类型的特征。在包含四个主要生物医学实体类型的五个BioNER基准数据集的实验中，即使只有有限的训练数据可用，我们的模型也大大超过了最先进的系统和其他神经网络模型。进一步的分析表明，大量的性能收益来自不同的生物医学实体之间共享字符和字级的信息。该方法为文本挖掘方法创造了新的机会，帮助生物医学科学家更好地利用生物医学文献中的知识。

##### URL
[http://arxiv.org/abs/1801.09851](http://arxiv.org/abs/1801.09851)

##### PDF
[http://arxiv.org/pdf/1801.09851](http://arxiv.org/pdf/1801.09851)

