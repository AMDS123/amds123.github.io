---
layout: post
title: "A More Human Way to Play Computer Chess"
date: 2018-06-11 08:37:36
categories: arXiv_AI
tags: arXiv_AI
author: Kieran Greer
mathjax: true
---

* content
{:toc}

##### Abstract
The idea of dynamic move chains has been described in a preceding paper [13]. Re-using an earlier piece of search allows the tree to be forward-pruned, which is known to be dangerous, because that can remove new information which would only be realised through a more exhaustive search process. This paper has added to the forward-pruning technique by using 'Move Tables' that can act in the same way as Transposition Tables, but for moves not positions. They use an efficient memory structure and has put the design into the context of short and long-term memories. The long-term memory uses a play path with weight reinforcement, while the short-term memory can be immediately added or removed. Therefore, 'long branches' can play a short path, before returning to a full search at the resulting leaf nodes. Automatic feature analysis is now central to the search algorithm, where key squares and related squares can be generated automatically and used to guide the search process. Also using the analysis, if a search result is inferior, it can re-insert un-played moves that cover these key squares, thereby correcting those tactical errors. In particular, a type of move that the forward-pruning will fail on is recognised and a solution to that problem is suggested. This process reduces some gains made by forward-pruning but has created an intelligent framework that could make it more reliable. This has completed the theory of an earlier paper and resulted in a more human-like approach to searching for a chess move.

##### Abstract (translated by Google)
在前面的文章中已经描述了动态移动链的概念[13]。重新使用较早的搜索片段可以对树进行前向修剪，这已知是危险的，因为这可以移除只能通过更详尽的搜索过程才能实现的新信息。本文通过使用“移动表格”添加到前向修剪技术中，该表格可以与移位表格相同的方式起作用，但移动不是位置。他们使用高效的内存结构，并将设计纳入短期和长期记忆的环境中。长期记忆使用重力加强的播放路径，而短期记忆可以立即添加或删除。因此，“长分支”可以播放一条短路径，然后返回到生成的叶节点的完整搜索。自动特征分析现在是搜索算法的核心，其中可以自动生成关键方块和相关方块并用于指导搜索过程。同样使用分析，如果搜索结果较差，它可以重新插入覆盖这些关键方块的未播放动作，从而纠正这些战术错误。特别是，一种类型的向前修剪将失败的行动得到承认，并建议解决这个问题。这个过程减少了前向修剪所带来的一些收益，但创建了一个可以使其更可靠的智能框架。这已经完成了早期论文的理论，并导致了更像人类的方法来寻找国际象棋的举措。

##### URL
[http://arxiv.org/abs/1503.04333](http://arxiv.org/abs/1503.04333)

##### PDF
[http://arxiv.org/pdf/1503.04333](http://arxiv.org/pdf/1503.04333)

