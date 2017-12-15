---
layout: post
title: "FastText.zip: Compressing text classification models"
date: 2016-12-12 12:51:03
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification
author: Armand Joulin, Edouard Grave, Piotr Bojanowski, Matthijs Douze, Hérve Jégou, Tomas Mikolov
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of producing compact architectures for text classification, such that the full model fits in a limited amount of memory. After considering different solutions inspired by the hashing literature, we propose a method built upon product quantization to store word embeddings. While the original technique leads to a loss in accuracy, we adapt this method to circumvent quantization artefacts. Our experiments carried out on several benchmarks show that our approach typically requires two orders of magnitude less memory than fastText while being only slightly inferior with respect to accuracy. As a result, it outperforms the state of the art by a good margin in terms of the compromise between memory usage and accuracy.

##### Abstract (translated by Google)
我们考虑为文本分类生成紧凑体系结构的问题，以使整个模型适合有限的内存。在考虑哈希文献引发的不同解决方案之后，我们提出了一种基于产品量化来存储文字嵌入的方法。虽然原始技术导致准确性的损失，但是我们采用这种方法来规避量化假象。我们在几个基准测试中进行的实验表明，我们的方法通常需要比fastText少两个数量级的内存，而在精度方面稍差。因此，就内存使用和准确性之间的妥协而言，它的性能优于现有技术。

##### URL
[https://arxiv.org/abs/1612.03651](https://arxiv.org/abs/1612.03651)

##### PDF
[https://arxiv.org/pdf/1612.03651](https://arxiv.org/pdf/1612.03651)

