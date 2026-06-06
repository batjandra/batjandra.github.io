---
title: "Feedforward Mixing is as Sharp as it is Slow in Reverse"
collection: publications
category: workshops
permalink: /publication/feedforward-mixing-sharp-slow
excerpt: 'We analyze the feedforward mixing process in neural networks and establish backward mixing time as a key metric for evaluating information propagation.'
date: 2026-06-06
venue: 'ICML 2026 Workshop on Combining Theory and Benchmarks: Towards A Virtuous Cycle to Understand and Guarantee Foundation Model Performance (T&B)'
paperurl: 'https://openreview.net/pdf?id=7vuXbycHfO'
---

Deep learning architectures across diverse domains—including language modeling, audio-visual processing, and temporal graph modeling—fundamentally rely on feedforward computational graphs. Consequently, optimising these graph topologies is a major research focus. Recent theoretical work evaluates the efficacy of these graphs using two key metrics: forward mixing time $T_{fwd}(G)$ (the speed of information propagation) and normalised minimax fidelity $F(G)$ (the sharpness of information representation). In this work, we prove that, surprisingly, minimax fidelity is tightly upper-bounded by the \textit{backward} mixing time of computational graphs: $F(G) \le \frac{8}{3} \cdot T_{bwd}(G)$ for all feedforward graphs with a unique source and sink. Practically, this establishes a direct tradeoff, $F(G) \le \frac{8}{3} \cdot T_{fwd}(G)$, for symmetric graphs where $T_{fwd}(G) = T_{bwd}(G)$. In the uniform setting, because most common architectures—including fully-connected and sliding-window graphs—are symmetric, this exposes an unavoidable architectural limit: optimising for rapid information mixing necessitates a degradation in fidelity, and vice versa. More generally, i.e. if $T_{bwd}(G) = f(T_{fwd}(G))$ and consequently $F(G) \le f(T_{fwd}(G))$ for some function $f$, we show that $f$ is well-behaved and at most an $O(n)$ factor of $T_{fwd}(G)$ for both uniform and non-uniform graphs, where $n$ is the number of nodes in $G$. Our results, ultimately, establish backward mixing time as a key metric for evaluating information propagation in deep learning models.
