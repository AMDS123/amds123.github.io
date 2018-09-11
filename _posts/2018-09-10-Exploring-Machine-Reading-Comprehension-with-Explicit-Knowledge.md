---
layout: post
title: "Exploring Machine Reading Comprehension with Explicit Knowledge"
date: 2018-09-10 16:42:22
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction Relation
author: Chao Wang, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
To apply general knowledge to machine reading comprehension (MRC), we propose an innovative MRC approach, which consists of a WordNet-based data enrichment method and an MRC model named as Knowledge Aided Reader (KAR). The data enrichment method uses the semantic relations of WordNet to extract semantic level inter-word connections from each passage-question pair in the MRC dataset, and allows us to control the amount of the extraction results by setting a hyper-parameter. KAR uses the extraction results of the data enrichment method as explicit knowledge to assist the prediction of answer spans. According to the experimental results, the single model of KAR achieves an Exact Match (EM) of $72.4$ and an F1 Score of $81.1$ on the development set of SQuAD, and more importantly, by applying different settings in the data enrichment method to change the amount of the extraction results, there is a $2\%$ variation in the resulting performance of KAR, which implies that the explicit knowledge provided by the data enrichment method plays an effective role in the training of KAR.

##### Abstract (translated by Google)
为了将一般知识应用于机器阅读理解（MRC），我们提出了一种创新的MRC方法，该方法包括基于WordNet的数据丰富方法和名为知识辅助阅读器（KAR）的MRC模型。数据丰富方法使用WordNet的语义关系从MRC数据集中的每个通道 - 问题对中提取语义级别的词间连接，并允许我们通过设置超参数来控制提取结果的量。 KAR使用数据富集方法的提取结果作为显式知识来帮助预测答案跨度。根据实验结果，KAR的单一模型在SQUAD的开发集上实现了72.4美元的完全匹配（EM）和81.1美元的F1分数，更重要的是，通过在数据丰富方法中应用不同的设置来改变在提取结果的数量上，KAR的最终表现存在$ 2 \％$变化，这意味着数据丰富方法提供的显性知识在KAR的训练中起到了有效的作用。

##### URL
[http://arxiv.org/abs/1809.03449](http://arxiv.org/abs/1809.03449)

##### PDF
[http://arxiv.org/pdf/1809.03449](http://arxiv.org/pdf/1809.03449)

