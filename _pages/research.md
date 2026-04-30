---
permalink: /research_/
title: ""
author_profile: false
redirect_from: 
  - /research
  - /research.md
---

In general, my research spans game theory, online learning, multi-agent reinforcement learning and computational complexity, as well as their applications to agentic AI. 
The ultimate goal of my research is to develop theoretically principled solutions to algorithmic challenges, drawing inspiration from modern decision-making environments and AI, in order to bridge the gap between real-world application and fundamental computational understanding.
Below, I outline the main research pillars of my work:

### Game Theory & Online Learning: No-regret learning under imperfect information

In this research pillar, we investigate the convergence properties and structural guarantees of no-regret dynamics within environments characterized by information asymmetry and partial observability. 
Specifically, I'm particularly interested in studying *decentralized online learning in games* under imperfect information, where no-regret dynamics translate to computing game-theoretic equilibrium notions—such as *Nash equilibria* or *correlated equilibria*—as well as *adversarial settings* where the learner competes against powerful, best-in-hindsight benchmarks. 

#### _<font color="blue">Main results</font>_
- A kernelization framework for learning in *polyhedral games* under imperfect information (i.e., *bandit* and *semi-bandit*
feedback), which facilitates efficient implementation and sampling for the classical combinatorial bandit GeometricHedge/ComBand algorithm and the celebrated Exp3-IX algorithm [(NeurIPS 2025)](https://arxiv.org/abs/2509.20919). Our work provides state-of-the-art results for learning *coarse correlated equilibria* across iconic games, such as congestion games and Colonel Blotto, addressing various open questions in the field.
We also managed to provide the *first efficiently implementable algorithm* for *adversarial combinatorial bandits* that achieves *no swap regret* (that is, a strong notion of regret associated with correlated equilibria) with polylogarithmic dependence on the large action size of combinatorial bandits [(AISTATS 2026)](https://arxiv.org/abs/2602.02087).


### The computational complexity of non-convex optimization

The main direction of this research pillar investigates the computational complexity of fundamental problems in non-convex optimization. Our goal is to advance the computational understanding of finding *second-order stationary points* (SOSPs) in non-convex optimization. Such points are of remarkable interest for the ML/optimization community, since widely used optimizers—including Gradient Descent—can theoretically stuck in first-order stationary points (FOSPs) that may be *strict saddle points*. Therefore, our main research question is the following:

> *What is the computational complexity of avoiding strict saddle points both in unconstrained and constrained non-convex optimization?*

#### _<font color="blue">Our contribution and its significance</font>_
We prove that the problem is *PLS-complete* both in unconstrained [(ICML 2024)](https://openreview.net/forum?id=t8WDBcegae) and constrained [(arXiv 2026)](https://arxiv.org/abs/2604.02285) optimization. Our results imply that unless PLS $\subseteq$ PPAD (which is widely believed to do so), there exists no iterative algorithm with a continuous, efficiently implementable update rule (such Gradient descent or the Newton's method) for finding SOSPs! Thus, our results further imply that the inherent "discreteness" of PLS-hard problems fundamentally clashes with the requirement of algorithmic continuity. Moreover, 

### Agentic AI & Multi-Agent Reinforcement Learning





<br/>
(2025) <i><b> Enhancing Cooperative Multi-Agent Reinforcement Learning with State Modelling and Adversarial Exploration </b> </i> 
<br/> 
<u>A. Kontogiannis</u><sup>*</sup>, K. Papathanasiou<sup>*</sup>, Y. Shen, G. Stamou, M. Zavlanos and G. Vouros.
<br/>
_<font color="red">ICML 2025</font>_ [[paper](https://www.arxiv.org/abs/2505.05262)] [[code](https://github.com/ddaedalus/smpe/tree/main)]

<br/>
(2025) <i><b> An Extended Benchmarking of Multi-Agent Reinforcement Learning Algorithms in Complex Fully Cooperative Tasks </b> </i> 
<br/> 
G. Papadopoulos<sup>*</sup>, <u>A. Kontogiannis</u><sup>*</sup>, F. Papadopoulou, C. Poulianou, I. Koumentis and G. Vouros.
<br/>
_<font color="red">AAMAS 2025</font>_ [[paper](https://www.arxiv.org/abs/2502.04773?fbclid=IwZXh0bgNhZW0CMTAAAR0STD9oKF7IUu4fKUjMA_gBtADEwmaYDnz6RXsM4IhiTAp7H4MgMGmggMQ_aem_JyMoU6wDa2iyPMa-RrUxDQ)] [[code](https://github.com/AILabDsUnipi/pymarlzooplus)]


<br/>
(2024) <i><b> The Computational Complexity of Finding Second-Order Stationary Points </b> </i> 
<br/> 
<u>A. Kontogiannis</u><sup>*</sup>, V. Pollatos<sup>*</sup>, S. Kanellopoulos, P. Mertikopoulos, A. Pagourtzis and I. Panageas.
<br/>
_<font color="red">ICML 2024</font>_ []

