---
layout: default
title: "Horizon Summary: 2026-07-16 (EN)"
date: 2026-07-16
lang: en
---

> From 47 items, 3 important content pieces were selected

---

1. [Kimi K3: Frontier Open-Weight LLM with 1M Context](#item-1) ⭐️ 8.0/10
2. [Sony Deletes Purchased Movies from User Accounts](#item-2) ⭐️ 8.0/10
3. [QLoRA Default Learning Rate 2e-4 Suboptimal for Small Datasets](#item-3) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Kimi K3: Frontier Open-Weight LLM with 1M Context](https://www.kimi.com/en) ⭐️ 8.0/10

Moonshot AI has released Kimi K3, a frontier-level open-weight large language model with 2.8 trillion parameters and a 1M-token context window, now available via API with competitive pricing at $3/$15 per million input/output tokens. Kimi K3 is one of the largest open-weight models ever released, claiming performance second only to Claude Fable 5 and GPT-5.6 Sol, which could reshape the competitive landscape for open-source AI and provide a powerful alternative to proprietary frontier models. The model has 2.8 trillion parameters, making it the largest open-weight model to date, and features a 1M-token context window with no long-context surcharge. Full model weights and a technical report are promised in the coming days.

hackernews · vincent_s · Jul 16, 14:46 · [Discussion](https://news.ycombinator.com/item?id=48935342)

**Background**: Open-weight LLMs make their pre-trained weights publicly available, allowing developers to fine-tune and deploy them. A 1M-token context window enables processing of large documents or codebases in a single pass, reducing the need for retrieval-augmented generation. Kimi K3 is developed by Moonshot AI, a Chinese AI company that reportedly raised $500 million earlier this year.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kimi.com/en">Kimi AI with K3 | Built for Agentic Coding & Knowledge Work</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>
<li><a href="https://tokenmix.ai/blog/kimi-k3-developer-integration-guide-2026">Kimi K3 Developer Integration Guide: API, Routing, Migration Path</a></li>

</ul>
</details>

**Discussion**: Community comments highlight the model's massive 2.8T parameter count and note that its pricing matches Anthropic's Sonnet series, which is considered high for a Chinese open-weight model but justified if performance is truly frontier-level. Some users also shared cost examples, showing that rendering a complex image cost $0.25.

**Tags**: `#LLM`, `#open-source`, `#AI`, `#pricing`, `#context-length`

---

<a id="item-2"></a>
## [Sony Deletes Purchased Movies from User Accounts](https://www.techdirt.com/2026/07/15/sony-deletes-a-bunch-more-movies-from-the-accounts-of-people-who-bought-them/) ⭐️ 8.0/10

Sony has removed multiple movies from the digital libraries of users who believed they had purchased them, reigniting the debate over digital ownership. This incident underscores the fragility of digital ownership and may accelerate consumer distrust in digital-only ecosystems, potentially pushing users toward physical media or alternative platforms. The deletions occurred without prior notice, and affected titles include 'A Shaun The Sheep Movie: Farmageddon'. Sony has not provided a clear explanation or compensation.

hackernews · nekusar · Jul 16, 12:13 · [Discussion](https://news.ycombinator.com/item?id=48933419)

**Background**: Digital ownership is a legal gray area: when users click 'Buy', they often only acquire a revocable license, not the content itself. Sony's move follows its announcement that physical game discs will cease production by January 2028, signaling a shift to all-digital distribution.

**Discussion**: Commenters expressed outrage and frustration, with many noting the contradiction between Sony's push for digital-only sales and its deletion of purchased content. Some called for legal action against misleading 'Buy' buttons, while others speculated about the decline of console gaming.

**Tags**: `#digital rights`, `#consumer protection`, `#Sony`, `#gaming`, `#ownership`

---

<a id="item-3"></a>
## [QLoRA Default Learning Rate 2e-4 Suboptimal for Small Datasets](https://www.reddit.com/r/MachineLearning/comments/1uy1z8b/the_qlora_2e4_default_is_wrong_under_10k_samples/) ⭐️ 8.0/10

A Reddit user argues that the default QLoRA learning rate of 2e-4 is suboptimal for datasets under 10k samples, causing overfitting, and demonstrates that reducing it to 1e-4 significantly improves evaluation performance. This challenges a widely accepted default hyperparameter, affecting many practitioners fine-tuning on small datasets who may waste time blaming data quality instead of tuning the learning rate. The author reports that with 2e-4, the model overfits within the first epoch, while dropping to 1e-4 and increasing epochs from 3 to 5 led to a significant jump in evaluation metrics. The default 2e-4 originates from the Alpaca dataset (52k samples) and may not generalize to smaller datasets.

reddit · r/MachineLearning · /u/Pretty-Ad774 · Jul 16, 12:50

**Background**: QLoRA is a parameter-efficient fine-tuning method that combines 4-bit quantization of the base model with Low-Rank Adaptation (LoRA) adapters, enabling fine-tuning of large language models on consumer hardware. The learning rate is a critical hyperparameter that controls the step size during optimization; a too-high learning rate can cause overfitting on small datasets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.heulistic.com/blog/learning-rate-qlora-fine-tuning">What Learning Rate to Use for QLoRA Fine-Tuning</a></li>
<li><a href="https://insiderllm.com/guides/fine-tuning-local-lora-qlora/">Fine-Tuning LLMs on Consumer Hardware: LoRA and QLoRA Guide</a></li>
<li><a href="https://github.com/artidoro/qlora">GitHub - artidoro/qlora: QLoRA: Efficient Finetuning of ...</a></li>

</ul>
</details>

**Discussion**: The Reddit post generated significant discussion, with many users sharing similar experiences and agreeing that the default 2e-4 is often too high for small datasets. Some suggested even lower learning rates like 5e-5 or 1e-5, while others emphasized the importance of tuning learning rate per dataset rather than relying on defaults.

**Tags**: `#QLoRA`, `#fine-tuning`, `#learning rate`, `#hyperparameter tuning`, `#LLM`

---