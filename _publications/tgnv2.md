---
title: "Enhancing the Expressivity of Temporal Graph Networks via Source-Target Identification"
collection: publications
category: workshops
permalink: /publication/tgnv2
excerpt: 'We show that adding source-target identification to Temporal Graph Networks (TGNs) strictly increases its expressivity and demonstrate that the resulting architecture outperforms all TG methods in dynamic node affinity prediction on all TGB datasets.'
date: 2024-10-01
venue: 'NeurIPS Symmetry and Geometry in Neural Representations Workshop 2024'
paperurl: 'https://neurips.cc/virtual/2024/101413'
---

Despite the successful application of Temporal Graph Networks (TGNs) for tasks such as dynamic node classification and link prediction, they still perform poorly on the task of dynamic node affinity prediction -- where the goal is to predict 'how much' two nodes will interact in the future. In fact, simple heuristic approaches such as persistent forecasts and moving averages over ground-truth labels significantly and consistently outperform TGNs. Building on this observation, we find that computing heuristics over messages is an equally competitive approach, outperforming TGN and all current temporal graph (TG) models on dynamic node affinity prediction. In this paper, we prove that no formulation of TGN can represent persistent forecasting or moving averages over messages, and propose to enhance the expressivity of TGNs by adding source-target identification to each interaction event message. We show that this modification is required to represent persistent forecasting, moving averages, and the broader class of autoregressive models over messages. Our proposed method, TGNv2, significantly outperforms TGN and all current TG models on all Temporal Graph Benchmark (TGB) dynamic node affinity prediction datasets.