---
title: "T-GRAB: A Synthetic Diagnostic Benchmark for Learning on Temporal Graphs"
collection: publications
category: workshops
permalink: /publication/tgrab
excerpt: 'We design a temporal 'obstacle course' to systematically benchmarks the performance of TGNNs at carefully designed synthetic temporal reasoning tasks.'
date: 2025-07-14
venue: 'KDD 2025 Machine Learning on Graphs in the Era of Generative Artificial Intelligence Workshop (Oral)'
paperurl: 'https://arxiv.org/abs/2507.10183
---
Dynamic graph learning methods have recently emerged as powerful tools for modelling relational data evolving through time. However, despite extensive benchmarking efforts, it remains unclear whether current Temporal Graph Neural Networks (TGNNs) effectively capture core temporal patterns such as periodicity, cause-and-effect, and long-range dependencies. In this work, we introduce the Temporal Graph Reasoning Benchmark (T-GRAB), a comprehensive set of synthetic tasks designed to systematically probe the capabilities of TGNNs to reason across time. T-GRAB provides controlled, interpretable tasks that isolate key temporal skills: counting/memorizing periodic repetitions, inferring delayed causal effects, and capturing long-range dependencies over both spatial and temporal dimensions. We evaluate 11 temporal graph learning methods on these tasks, revealing fundamental shortcomings in their ability to generalize temporal patterns. Our findings offer actionable insights into the limitations of current models, highlight challenges hidden by traditional real-world benchmarks, and motivate the development of architectures with stronger temporal reasoning abilities. The code for T-GRAB can be found at: https://github.com/alirezadizaji/T-GRAB.  