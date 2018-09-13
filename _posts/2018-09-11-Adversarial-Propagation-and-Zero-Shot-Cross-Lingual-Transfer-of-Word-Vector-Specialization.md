---
layout: post
title: "Adversarial Propagation and Zero-Shot Cross-Lingual Transfer of Word Vector Specialization"
date: 2018-09-11 21:08:00
categories: arXiv_CL
tags: arXiv_CL Adversarial Knowledge Tracking Relation
author: Edoardo Maria Ponti, Ivan Vuli&#x107;, Goran Glava&#x161;, Nikola Mrk&#x161;i&#x107;, Anna Korhonen
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic specialization is the process of fine-tuning pre-trained distributional word vectors using external lexical knowledge (e.g., WordNet) to accentuate a particular semantic relation in the specialized vector space. While post-processing specialization methods are applicable to arbitrary distributional vectors, they are limited to updating only the vectors of words occurring in external lexicons (i.e., seen words), leaving the vectors of all other words unchanged. We propose a novel approach to specializing the full distributional vocabulary. Our adversarial post-specialization method propagates the external lexical knowledge to the full distributional space. We exploit words seen in the resources as training examples for learning a global specialization function. This function is learned by combining a standard L2-distance loss with an adversarial loss: the adversarial component produces more realistic output vectors. We show the effectiveness and robustness of the proposed method across three languages and on three tasks: word similarity, dialog state tracking, and lexical simplification. We report consistent improvements over distributional word vectors and vectors specialized by other state-of-the-art specialization frameworks. Finally, we also propose a cross-lingual transfer method for zero-shot specialization which successfully specializes a full target distributional space without any lexical knowledge in the target language and without any bilingual data.

##### Abstract (translated by Google)
语义特化是使用外部词汇知识（例如，WordNet）微调预训练的分布式词向量以强调专用向量空间中的特定语义关系的过程。虽然后处理专门化方法适用于任意分布向量，但它们仅限于更新外部词典中出现的词的向量（即，看到的词），而使所有其他词的向量保持不变。我们提出了一种专门用于完整分布式词汇的新方法。我们的对抗后专业化方法将外部词汇知识传播到完整的分布空间。我们利用资源中的词语作为学习全球专业化功能的训练样例。通过将标准L2距离损失与对抗性损失相结合来学习该函数：对抗性分量产生更逼真的输出向量。我们展示了所提出的方法在三种语言和三个任务中的有效性和鲁棒性：单词相似度，对话状态跟踪和词汇简化。我们报告了对其他最先进的专业化框架专用的分布式词向量和向量的持续改进。最后，我们还提出了一种用于零射击专业化的跨语言转移方法，该方法成功地专门化了一个完整的目标分布空间，而没有任何目标语言的词汇知识，也没有任何双语数据。

##### URL
[http://arxiv.org/abs/1809.04163](http://arxiv.org/abs/1809.04163)

##### PDF
[http://arxiv.org/pdf/1809.04163](http://arxiv.org/pdf/1809.04163)

