---
title: "Action chunking transformer-based imitation learning with dynamic programming optimization for low-cost robotic assembly tasks"
date: 2026-09-16
author: "jonahortega"
issue: https://github.com/deepcharles/macs3050-journal/issues/82
---

### Students

Jonah Ortega

### Question 1: Reference

```bibtex
@article{li_action_2026,
	title = {Action chunking transformer-based imitation learning with dynamic programming optimization for low-cost robotic assembly tasks},
	copyright = {2026 The Author(s)},
	issn = {2045-2322},
	url = {https://www.nature.com/articles/s41598-026-63709-3},
	doi = {10.1038/s41598-026-63709-3},
	abstract = {Nowadays, many studies focus on using AI tools to improve the performance of manipulators in fields such as assembly. One popular approach is the Action Chunking Transformer (ACT), which enables robots to execute assembly tasks more efficiently. However, this method still faces challenges in achieving reliable assembly performance, particularly for low-cost manipulators with limited mechanical repeatability. To address this issue, this paper proposes a novel Dynamic Programming–based Action Chunking Transformer (DP-ACT) framework. By integrating dynamic programming into the ACT inference chain, the method provides local trajectory correction while maintaining the implemented control-loop frequency. The proposed framework was implemented on a low-cost SO100 robotic manipulator equipped with Feetech actuators and evaluated through a three-stage precision-oriented assembly task. A total of 160 teleoperated demonstrations were collected for offline training, and 100 assembly trials were conducted for evaluation. Experimental results indicate that DP-ACT increases the assembly success rate from 62\% to 82\% and significantly improves trajectory efficiency while maintaining comparable task completion times.},
	language = {en},
	urldate = {2026-09-08},
	journal = {Scientific Reports},
	publisher = {Nature Publishing Group},
	author = {Li, Yuhang and Li, Deping},
	month = aug,
	year = {2026},
	keywords = {Engineering, Mathematics and computing},
}
```

### Question 2: Research question

# The research question is always posed for the purpose of the reader and the writer, gives all members a clear understanding of what the paper is trying to achieve. Without a Research question it is difficult to truly understand the topic.

### Question 3: Data

# The Who is robotic assembly tasks, the what is integration with dynamic programming optimization, the where is in China, the when is 2026, and the how it was collected is through machine learning.

### Question 4: Results

# The most important results were that paper addresses the reliability requirements of low-cost robotic assembly. The most significant results of optimization resulted in 62% to 82% improved efficiency.


### Question 5: Cited articles

# The total articles cited are 23 in total. 

# [3] Zhao, T.Z., Kumar, V., Levine, S., & Finn, C. — Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware (2023)

# [17] Styrud, J., Mayr, M., Hellsten, E., Krueger, V., & Smith, C. — BeBOP – Combining Reactive Planning and Bayesian Optimization to Solve Robotic Manipulation Tasks (2023)

# [20] Vaswani, A. et al. — Attention is All You Need (2017)

### Question 6: Questions for the authors

- Why does adding this "DP" step make the robot better at grabbing things not really better at fitting the pieces together?
- This test was run on a cheap robot arm would it be different if another one was used?
- If the lighting in the room is poor does it just mess up a little or just break.
