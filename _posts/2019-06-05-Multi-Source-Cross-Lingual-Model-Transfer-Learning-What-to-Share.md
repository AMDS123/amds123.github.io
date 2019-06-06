---
layout: post
title: "Multi-Source Cross-Lingual Model Transfer: Learning What to Share"
date: 2019-06-05 04:04:07
categories: arXiv_CL
tags: arXiv_CL Adversarial Text_Classification Embedding Transfer_Learning Classification
author: Xilun Chen, Ahmed Hassan Awadallah, Hany Hassan, Wei Wang, Claire Cardie
mathjax: true
---

* content
{:toc}

##### Abstract
Modern NLP applications have enjoyed a great boost utilizing neural networks models. Such deep neural models, however, are not applicable to most human languages due to the lack of annotated training data for various NLP tasks. Cross-lingual transfer learning (CLTL) is a viable method for building NLP models for a low-resource target language by leveraging labeled data from other (source) languages. In this work, we focus on the multilingual transfer setting where training data in multiple source languages is leveraged to further boost target language performance. 
 Unlike most existing methods that rely only on language-invariant features for CLTL, our approach coherently utilizes both language-invariant and language-specific features at instance level. Our model leverages adversarial networks to learn language-invariant features, and mixture-of-experts models to dynamically exploit the similarity between the target language and each individual source language. This enables our model to learn effectively what to share between various languages in the multilingual setup. Moreover, when coupled with unsupervised multilingual embeddings, our model can operate in a zero-resource setting where neither target language training data nor cross-lingual resources are available. Our model achieves significant performance gains over prior art, as shown in an extensive set of experiments over multiple text classification and sequence tagging tasks including a large-scale industry dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03552](http://arxiv.org/abs/1810.03552)

##### PDF
[http://arxiv.org/pdf/1810.03552](http://arxiv.org/pdf/1810.03552)

