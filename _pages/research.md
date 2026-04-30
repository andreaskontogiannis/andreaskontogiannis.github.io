---
permalink: /research_/
title: ""
author_profile: false
redirect_from: 
  - /research
  - /research.md
---

In general, my research spans game theory, online learning, multi-agent reinforcement learning and computational complexity, and their applications to agentic AI. 
The ultimate goal of my research is to develop theoretically principled solutions to algorithmic challenges, drawing inspiration from modern decision-making environments and AI, in order to bridge the gap between real-world application and fundamental computational understanding.
Below, I outline the main research pillars of my work:

### Game Theory & Online Learning: No-regret learning under imperfect information

In this research pillar, we investigate the convergence properties and structural guarantees of no-regret dynamics within environments characterized by information asymmetry and partial observability. 
Specifically, I'm particularly interested in studying *decentralized online learning in games* under imperfect information, where no-regret dynamics translate to computing game-theoretic equilibrium notions—such as Nash equilibria or correlated equilibria—as well as *adversarial settings* where the learner competes against powerful, best-in-hindsight benchmarks. 

#### Main results
- A kernelization framework for learning in *polyhedral games* under imperfect information (i.e., *bandit* and *semi-bandit feedback*), which facilitates efficient implementation and sampling for the widely used GeometricHedge/ComBand and Exp3-IX algorithms [(NeurIPS 2025)](https://arxiv.org/abs/2509.20919). Our work provides state-of-the-art results for learning *coarse correlated equilibria* across iconic games, such as congestion games and Colonel Blotto, addressing various open questions in the field.
- *No swap regret in combinatorial bandits* [(AISTATS 2026)](https://arxiv.org/abs/2602.02087): One of the most challenging questions in the online learning community has been how to design computationally efficient, no-swap-regret algorithms for which both the swap regret (a powerful benchmark associated with correlated equilibria) and the per-iteration complexity depend polylogarithmically on the possibly very large number of the available actions. Although this question has been recently resolved for the standard experts setting and the established approaches are applicable to adversarial combinatorial bandits (e.g., the slate selection problem), they fail to achieve the desired polylogarithmic dependence of the swap regret and the per-iteration complexity on the number of actions. Our work provides the first efficiently implementable algorithm that achieves no-swap-regret with polylogarithmic dependence on the large action space of combinatorial bandits.

### The computational complexity of non-convex optimization


### Agentic AI & Multi-Agent Reinforcement Learning


<br/>
(2026) <i><b> 
The Computational Complexity of Avoiding Strict Saddle Points in Constrained Optimization </b> </i> 
<br/> 
[αβ] <u>A. Kontogiannis</u>, I. Panageas and V. Pollatos.
<br/>
_<font color="red">arXiv preprint (2026)</font>_ [[paper](https://arxiv.org/abs/2604.02285)]


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
_<font color="red">ICML 2024</font>_ [[paper](https://openreview.net/forum?id=t8WDBcegae)]

