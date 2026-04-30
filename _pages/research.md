---
permalink: /research_/
title: ""
author_profile: true
redirect_from: 
  - /research
  - /research.md
---

In general, my research spans game theory, online learning, multi-agent reinforcement learning and computational complexity, as well as their applications to agentic AI. 
The ultimate goal of my research is to develop theoretically principled solutions to algorithmic challenges, drawing inspiration from modern decision-making environments and AI, in order to bridge the gap between real-world application and fundamental computational understanding.
Below, I outline the main research pillars of my work:

### _<font color="MediumSeaGreen">Game Theory & Online Learning: No-regret learning under imperfect information</font>_

In this research pillar, we investigate the convergence properties and structural guarantees of no-regret dynamics within environments characterized by information asymmetry and partial observability. 
Specifically, I'm particularly interested in studying *decentralized online learning in games* under imperfect information, where no-regret dynamics translate to computing game-theoretic equilibrium notions—such as *Nash equilibria* or *correlated equilibria*—as well as *adversarial settings* where the learner competes against powerful, best-in-hindsight benchmarks. 

#### _<font color="blue">Main results</font>_
- A kernelization framework for learning in *polyhedral games* under imperfect information (i.e., *bandit* and *semi-bandit*
feedback), which facilitates efficient implementation and sampling for the classical combinatorial bandit <span style="font-variant: small-caps;">GeometricHedge</span>/<span style="font-variant: small-caps;">ComBand</span> algorithm and the celebrated <span style="font-variant: small-caps;">Exp3-IX</span> algorithm [(NeurIPS 2025)](https://arxiv.org/abs/2509.20919). Our work provides state-of-the-art results for learning *coarse correlated equilibria* across iconic games, such as congestion games and Colonel Blotto, addressing various open questions in the field.
We also managed to provide the *first efficiently implementable algorithm* for *adversarial combinatorial bandits* that achieves *no swap regret* (that is, a strong notion of regret associated with correlated equilibria) with polylogarithmic dependence on the large action size of combinatorial bandits [(AISTATS 2026)](https://arxiv.org/abs/2602.02087).

### _<font color="MediumSeaGreen">The computational complexity of non-convex optimization</font>_

The main direction of this research pillar investigates the computational complexity of fundamental problems in non-convex optimization. Our goal is to advance the computational understanding of finding *second-order stationary points* (SOSPs) in non-convex optimization. Such points are of remarkable interest for the ML/optimization community, since widely used optimizers—including Gradient Descent—can theoretically stuck in first-order stationary points (FOSPs) that may be problematic *strict saddle points*. Therefore, our main research question is the following:

> *What is the computational complexity of avoiding strict saddle points both in unconstrained and constrained non-convex optimization?*

#### _<font color="blue">Our contribution and its significance</font>_
We proved that the problem is *PLS-complete* both in unconstrained [(ICML 2024)](https://openreview.net/forum?id=t8WDBcegae) and constrained [(arXiv 2026)](https://arxiv.org/abs/2604.02285) optimization; thereby resolving important open questions in the field. Our results imply that unless PLS $\subseteq$ PPAD (which is widely believed to do so), there exists no iterative algorithm with a continuous, efficiently implementable update rule (such Gradient Descent or the Newton's method) for finding SOSPs! Last but not least, our result in the constrained setting yields the first problem defined in a compact domain to be shown PLS-complete beyond the canonical <span style="font-variant: small-caps;">Real-LocalOpt</span>.

### _<font color="MediumSeaGreen">Agentic AI & Multi-agent reinforcement learning</font>_

The main direction of this research pillar is to study how AI agents effectively coordinate toward shared objectives in complex, fully cooperative environments. In particular, we develop novel algorithmic frameworks and methodologies based on *multi-agent reinforcement learning (MARL)*. Our ultimate goal is to advance our understanding on the limits of *decentralized execution*, as well as explore *agent/state modelling* paradigms for minimizing the communication requirements of multi-agent systems, possibly under safety constraints. 

#### _<font color="blue">Main results</font>_
- A novel MARL algorithm which leverages a novel state modelling framework for enhancing policy optimization and joint exploration in distributed partially observable environments where agents share no communication channels during execution [ICML 2025](https://www.arxiv.org/abs/2505.05262). Experimentally, we demonstrated that our method outperforms state-of-the-art MARL algorithms in complex fully cooperative tasks from the well-established MPE, LBF, and RWARE benchmarks.
- In [AAMAS 2025](https://www.arxiv.org/abs/2502.04773?fbclid=IwZXh0bgNhZW0CMTAAAR0STD9oKF7IUu4fKUjMA_gBtADEwmaYDnz6RXsM4IhiTAp7H4MgMGmggMQ_aem_JyMoU6wDa2iyPMa-RrUxDQ), we highlight the crucial need for expanding systematic MARL evaluation across a wider array of existing benchmarks, showing that many algorithms, hailed as state-of-the-art mostly on the widely used SMAC benchmark, may significantly underperform standard MARL baselines on fully cooperative testbeds.


Furthermore, we investigate how *LLM-empowered agents* can act in challenging social deduction games—such as *Among Us*—that is, dynamic multi-agent environments of imperfect information characterized by a fundamental asymmetry: an informed minority operates against an uninformed majority. Such games are of remarkable interest, as they often demand that a player build and sustain a robust internal world model to accurately track the hidden states of others and deduce topological constraints while identifying, or even leveraging *deceptive strategies*.
