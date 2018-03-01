---
layout: post
title: "Simultaneously Self-Attending to All Mentions for Full-Abstract Biological Relation Extraction"
date: 2018-02-28 18:17:40
categories: arXiv_CL
tags: arXiv_CL OCR Relation_Extraction Attention Prediction Relation
author: Patrick Verga, Emma Strubell, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Most work in relation extraction forms a prediction by looking at a short span of text within a single sentence containing a single entity pair mention. This approach often does not consider interactions across mentions, requires redundant computation for each mention pair, and ignores relationships expressed across sentence boundaries. These problems are exacerbated by the document- (rather than sentence-) level annotation common in biological text. In response, we propose a model which simultaneously predicts relationships between all mention pairs in a document. We form pairwise predictions over entire paper abstracts using an efficient self-attention encoder. All-pairs mention scores allow us to perform multi-instance learning by aggregating over mentions to form entity pair representations. We further adapt to settings without mention-level annotation by jointly training to predict named entities and adding a corpus of weakly labeled data. In experiments on two Biocreative benchmark datasets, we achieve state of the art performance on the Biocreative V Chemical Disease Relation dataset for models without external KB resources. We also introduce a new dataset an order of magnitude larger than existing human-annotated biological information extraction datasets and more accurate than distantly supervised alternatives.

##### Abstract (translated by Google)
大多数关系抽取工作通过在包含单个实体对提及的单个句子中查看短文本来形成预测。这种方法通常不会考虑所提及的交互作用，需要对每个提及对进行冗余计算，而忽略跨越句子边界表达的关系。这些问题因生物文本中常见的文档（而非句子）级别注释而加剧。作为回应，我们提出了一个同时预测文档中所有提及对之间关系的模型。我们使用高效的自我注意编码器在整个纸张摘要上形成两两预测。所有对提及分数允许我们通过聚合提及来形成实体对表示来执行多实例学习。我们通过联合训练来预测命名实体并添加弱标记数据的语料库，从而进一步适应设置而不提供提示级别的注释。在两个Biocreative基准数据集的实验中，我们在没有外部KB资源的模型的Biocreative V Chemical Disease Relation数据集上实现了最先进的性能。我们还引入了一个新的数据集，其数量比现有的人类注释生物信息提取数据集大一个数量级，并且比远程监督的替代数据更准确。

##### URL
[http://arxiv.org/abs/1802.10569](http://arxiv.org/abs/1802.10569)

##### PDF
[http://arxiv.org/pdf/1802.10569](http://arxiv.org/pdf/1802.10569)

