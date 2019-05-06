---
layout: post
title: "FReD: Automated Debugging via Binary Search through a Process Lifetime"
date: 2012-12-20 19:39:10
categories: arXiv_CV
tags: arXiv_CV
author: Kapil Arya, Tyler Denniston, Ana-Maria Visan, Gene Cooperman
mathjax: true
---

* content
{:toc}

##### Abstract
Reversible debuggers have been developed at least since 1970. Such a feature is useful when the cause of a bug is close in time to the bug manifestation. When the cause is far back in time, one resorts to setting appropriate breakpoints in the debugger and beginning a new debugging session. For these cases when the cause of a bug is far in time from its manifestation, bug diagnosis requires a series of debugging sessions with which to narrow down the cause of the bug. For such "difficult" bugs, this work presents an automated tool to search through the process lifetime and locate the cause. As an example, the bug could be related to a program invariant failing. A binary search through the process lifetime suffices, since the invariant expression is true at the beginning of the program execution, and false when the bug is encountered. An algorithm for such a binary search is presented within the FReD (Fast Reversible Debugger) software. It is based on the ability to checkpoint, restart and deterministically replay the multiple processes of a debugging session. It is based on GDB (a debugger), DMTCP (for checkpoint-restart), and a custom deterministic record-replay plugin for DMTCP. FReD supports complex, real-world multithreaded programs, such as MySQL and Firefox. Further, the binary search is robust. It operates on multi-threaded programs, and takes advantage of multi-core architectures during replay.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1212.5204](https://arxiv.org/abs/1212.5204)

##### PDF
[https://arxiv.org/pdf/1212.5204](https://arxiv.org/pdf/1212.5204)

