---
title: "Fine-Tuning Large Language Models to Appropriately Abstain via Semantic Entropy"
collection: publications
category: workshops
permalink: /publication/fine-tuning-llms-semantic-entropy
excerpt: 'We fine-tune LLMs using semantic entropy to make them abstain from answering uncertain questions.'
date: 2024-10-02
venue: 'NeurIPS Safe Generative AI Workshop 2024'
paperurl: 'https://arxiv.org/abs/2410.17234'
---

Large Language Models (LLMs) are known to hallucinate, whereby they generate plausible but inaccurate text. This phenomenon poses significant risks in critical applications, such as medicine or law, necessitating robust hallucination mitigation strategies. While recent works have proposed fine-tuning methods to teach LLMs to abstain from answering questions beyond their knowledge or capabilities, these methods rely on the existence of ground-truth labels or are limited to short-form responses. To address these limitations, we propose fine-tuning using semantic entropy, an uncertainty measure derived from introspection into the model which does not require external labels. We demonstrate that our approach matches or outperforms models fine-tuned using prior work and achieves strong performance for both short and long-form generations on a range of datasets.