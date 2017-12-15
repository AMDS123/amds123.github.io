---
layout: post
title: "Yara Parser: A Fast and Accurate Dependency Parser"
date: 2015-03-24 18:45:13
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Mohammad Sadegh Rasooli, Joel Tetreault
mathjax: true
---

* content
{:toc}

##### Abstract
Dependency parsers are among the most crucial tools in natural language processing as they have many important applications in downstream tasks such as information retrieval, machine translation and knowledge acquisition. We introduce the Yara Parser, a fast and accurate open-source dependency parser based on the arc-eager algorithm and beam search. It achieves an unlabeled accuracy of 93.32 on the standard WSJ test set which ranks it among the top dependency parsers. At its fastest, Yara can parse about 4000 sentences per second when in greedy mode (1 beam). When optimizing for accuracy (using 64 beams and Brown cluster features), Yara can parse 45 sentences per second. The parser can be trained on any syntactic dependency treebank and different options are provided in order to make it more flexible and tunable for specific tasks. It is released with the Apache version 2.0 license and can be used for both commercial and academic purposes. The parser can be found at this https URL

##### Abstract (translated by Google)
依赖语法分析器是自然语言处理中最重要的工具，因为它们在信息检索，机器翻译和知识获取等下游任务中有许多重要的应用。我们介绍了Yara Parser，它是一个基于arc-eager算法和波束搜索的快速而准确的开源依赖解析器。它在标准的WSJ测试集上达到93.32的未标记的准确性，将其列为最高依赖性解析器之一。在最快的时候，YARA在贪婪模式下（1波束）可以每秒解析大约4000个句子。在对精度进行优化时（使用64个波束和Brown簇特征），Yara可以每秒解析45个句子。解析器可以在任何语法依赖树库上进行训练，并提供不同的选项以使其对于特定任务更灵活和可调。它与Apache版本2.0许可证一起发布，可用于商业和学术用途。解析器可以在这个https URL找到

##### URL
[https://arxiv.org/abs/1503.06733](https://arxiv.org/abs/1503.06733)

##### PDF
[https://arxiv.org/pdf/1503.06733](https://arxiv.org/pdf/1503.06733)

