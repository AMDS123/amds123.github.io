---
layout: post
title: "Complex Sequential Question Answering: Towards Learning to Converse Over Linked Question Answer Pairs with a Knowledge Graph"
date: 2018-01-31 06:40:40
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge QA Face Quantitative
author: Amrita Saha, Vardaan Pahuja, Mitesh M. Khapra, Karthik Sankaranarayanan, Sarath Chandar
mathjax: true
---

* content
{:toc}

##### Abstract
While conversing with chatbots, humans typically tend to ask many questions, a significant portion of which can be answered by referring to large-scale knowledge graphs (KG). While Question Answering (QA) and dialog systems have been studied independently, there is a need to study them closely to evaluate such real-world scenarios faced by bots involving both these tasks. Towards this end, we introduce the task of Complex Sequential QA which combines the two tasks of (i) answering factual questions through complex inferencing over a realistic-sized KG of millions of entities, and (ii) learning to converse through a series of coherently linked QA pairs. Through a labor intensive semi-automatic process, involving in-house and crowdsourced workers, we created a dataset containing around 200K dialogs with a total of 1.6M turns. Further, unlike existing large scale QA datasets which contain simple questions that can be answered from a single tuple, the questions in our dialogs require a larger subgraph of the KG. Specifically, our dataset has questions which require logical, quantitative, and comparative reasoning as well as their combinations. This calls for models which can: (i) parse complex natural language questions, (ii) use conversation context to resolve coreferences and ellipsis in utterances, (iii) ask for clarifications for ambiguous queries, and finally (iv) retrieve relevant subgraphs of the KG to answer such questions. However, our experiments with a combination of state of the art dialog and QA models show that they clearly do not achieve the above objectives and are inadequate for dealing with such complex real world settings. We believe that this new dataset coupled with the limitations of existing models as reported in this paper should encourage further research in Complex Sequential QA.

##### Abstract (translated by Google)
与聊天机器人交谈时，人类通常会提出许多问题，其中很大一部分可以通过参考大型知识图（KG）来回答。虽然问答（QA）和对话系统是独立研究的，但有必要仔细研究它们，以评估涉及这两项任务的机器人所面临的真实场景。为此，我们介绍复杂序列QA的任务，它把两个任务结合起来：（i）通过复杂的推理，通过现实规模的千百万实体KG来回答事实问题，（ii）通过一系列连贯的学习来交流链接QA对。通过劳动密集型的半自动化流程，涉及内部和众包的员工，我们创建了一个包含大约200K对话框的数据集，共计160万转。而且，与现有的包含简单问题的大规模QA数据集不同，我们对话中的问题需要KG的更大的子图。具体来说，我们的数据集有问题，需要逻辑，定量和比较推理，以及他们的组合。这需要模型能够：（i）解析复杂的自然语言问题，（ii）使用会话上下文来解决话语中的共同点和省略，（iii）要求澄清模棱两可的查询，最后（iv）检索相关的子图KG来回答这样的问题。然而，我们结合最先进的对话和QA模型进行的实验表明，他们显然没有达到上述目标，也不足以应付这种复杂的现实环境。我们认为，这个新的数据集加上本文中报道的现有模型的局限性，应该鼓励复杂序列QA的进一步研究。

##### URL
[http://arxiv.org/abs/1801.10314](http://arxiv.org/abs/1801.10314)

##### PDF
[http://arxiv.org/pdf/1801.10314](http://arxiv.org/pdf/1801.10314)

