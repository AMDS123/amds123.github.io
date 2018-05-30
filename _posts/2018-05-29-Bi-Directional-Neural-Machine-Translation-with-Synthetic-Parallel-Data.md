---
layout: post
title: "Bi-Directional Neural Machine Translation with Synthetic Parallel Data"
date: 2018-05-29 01:45:22
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xing Niu, Michael Denkowski, Marine Carpuat
mathjax: true
---

* content
{:toc}

##### Abstract
Despite impressive progress in high-resource settings, Neural Machine Translation (NMT) still struggles in low-resource and out-of-domain scenarios, often failing to match the quality of phrase-based translation. We propose a novel technique that combines back-translation and multilingual NMT to improve performance in these difficult cases. Our technique trains a single model for both directions of a language pair, allowing us to back-translate source or target monolingual data without requiring an auxiliary model. We then continue training on the augmented parallel data, enabling a cycle of improvement for a single model that can incorporate any source, target, or parallel data to improve both translation directions. As a byproduct, these models can reduce training and deployment costs significantly compared to uni-directional models. Extensive experiments show that our technique outperforms standard back-translation in low-resource scenarios, improves quality on cross-domain tasks, and effectively reduces costs across the board.

##### Abstract (translated by Google)
尽管在资源丰富的环境中取得了令人瞩目的进步，但神经机器翻译（NMT）仍然在低资源和域外情况下挣扎，往往无法与短语翻译的质量相匹配。我们提出了一种新技术，结合了回译和多语种NMT，以提高这些困难情况下的表现。我们的技术针对语言对的两个方向训练单一模型，使我们能够在不需要辅助模型的情况下回溯源或目标单语数据。然后，我们继续对增强后的并行数据进行培训，为可以结合任何源，目标或并行数据的单个模型实现一个改进循环，以改善两种翻译方向。作为副产品，与单向模型相比，这些模型可显着降低培训和部署成本。大量的实验表明，我们的技术在低资源情况下优于标准的后向转换，提高了跨域任务的质量，并有效地降低了整个板卡的成本。

##### URL
[http://arxiv.org/abs/1805.11213](http://arxiv.org/abs/1805.11213)

##### PDF
[http://arxiv.org/pdf/1805.11213](http://arxiv.org/pdf/1805.11213)

