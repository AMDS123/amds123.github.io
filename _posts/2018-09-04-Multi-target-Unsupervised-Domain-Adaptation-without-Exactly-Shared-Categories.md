---
layout: post
title: "Multi-target Unsupervised Domain Adaptation without Exactly Shared Categories"
date: 2018-09-04 09:18:19
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge
author: Huanhuan Yu, Menglei Hu, Songcan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain adaptation (UDA) aims to learn the unlabeled target domain by transferring the knowledge from the labeled source domain. To date, most of the existing works focus on the scenario of one source domain and one target domain (1S1T), and just a few works concern UDA of multiple source domains and one target domain (mS1T) for solving the insufficient knowledge problem with single source domain. While, to the best of our knowledge, almost no work concerns the scenario of one source domain and multiple target domains (1SmT). In the 1SmT, these unlabeled target domains may not necessarily share the same categories, therefore, in contrast to mS1T, 1SmT is more challenging. In this paper, we study such a new UDA scenario, and accordingly propose a UDA framework (PA-1SmT) through the model parameter adaptation among these target domains and the source domain. A key ingredient of our framework is that we firstly construct a model parameter dictionary which is shared not only between the source domain and the individual target domains but also among the multiple target domains. Then we use it to sparsely represent individual target parameters, which attains knowledge transfer among the domains. Such a new knowledge transfer is different from existing popular methods for UDA, such as subspace alignment, distribution matching etc., and can also be directly used for DA of privacy protection due to the fact that the knowledge is transferred just via the model parameters rather than data itself. Finally, our experimental results on three domain adaptation benchmark datasets demonstrate the superiority of our framework.

##### Abstract (translated by Google)
无监督域适应（UDA）旨在通过从标记的源域转移知识来学习未标记的目标域。迄今为止，大多数现有工作都集中在一个源域和一个目标域（1S1T）的场景中，只有少数工作涉及多个源域的UDA和一个目标域（mS1T），以解决单个知识问题不足的问题。源域。虽然，据我们所知，几乎没有工作涉及一个源域和多个目标域（1SmT）的场景。在1SmT中，这些未标记的目标域可能不一定共享相同的类别，因此，与mS1T相比，1SmT更具挑战性。在本文中，我们研究了这样一个新的UDA场景，并通过这些目标域和源域之间的模型参数自适应提出了UDA框架（PA-1SmT）。我们框架的一个关键要素是我们首先构建一个模型参数字典，它不仅在源域和单个目标域之间共享，而且在多个目标域之间共享。然后我们用它来稀疏地表示各个目标参数，从而实现域之间的知识转移。这种新的知识转移不同于现有的UDA流行方法，如子空间对齐，分布匹配等，也可以直接用于隐私保护的DA，因为知识只是通过模型参数传递而不是比数据本身。最后，我们对三个域适应基准数据集的实验结果证明了我们框架的优越性。

##### URL
[http://arxiv.org/abs/1809.00852](http://arxiv.org/abs/1809.00852)

##### PDF
[http://arxiv.org/pdf/1809.00852](http://arxiv.org/pdf/1809.00852)

