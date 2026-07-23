---
layout: default
title: "Horizon Summary: 2026-07-23 (EN)"
date: 2026-07-23
lang: en
---

> From 42 items, 3 important content pieces were selected

---

1. [SkewAdam cuts MoE optimizer memory by 97%](#item-1) ⭐️ 9.0/10
2. [Startup founders urge Trump to keep Chinese open-weight AI accessible](#item-2) ⭐️ 8.0/10
3. [Prompt Injection Found in NeurIPS 2026 Paper PDF](#item-3) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [SkewAdam cuts MoE optimizer memory by 97%](https://www.reddit.com/r/MachineLearning/comments/1v38k1m/skewadam_a_tiered_optimizer_that_cuts_moe_state/) ⭐️ 9.0/10

SkewAdam introduces a tiered optimizer state allocation that reduces MoE training memory by 97.4%, enabling a 6.7B MoE model to fit on a single 40GB GPU. This breakthrough dramatically lowers the hardware barrier for training large MoE models, allowing researchers with consumer GPUs to experiment with state-of-the-art architectures. SkewAdam allocates full momentum and factored second moment to backbone parameters (5%), only factored second moment to experts (95%), and exact second moment to the router (<0.01%). The optimizer state drops from 50.6 GB to 1.29 GB, and peak training memory from 81.4 GB to 31.3 GB.

reddit · r/MachineLearning · /u/Kooky-Ad-4124 · Jul 22, 07:04

**Background**: Mixture-of-Experts (MoE) models scale model capacity without proportionally increasing computation by using multiple specialized sub-networks (experts) activated per input. However, training MoEs is memory-intensive because the optimizer state (e.g., momentum and variance for AdamW) often dominates the memory budget, sometimes exceeding the model weights themselves.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/nuemaan/skewadam">GitHub - nuemaan/ skewadam : Tiered optimizer state allocation for...</a></li>
<li><a href="https://arxiv.org/pdf/2607.19058">Where Should Optimizer State Live? Tiered State Allocation for...</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion is highly positive, with users praising the practical impact and asking about convergence guarantees and integration with existing frameworks. The author actively responds to technical questions, confirming that SkewAdam matches AdamW convergence while using a fraction of the memory.

**Tags**: `#Mixture-of-Experts`, `#Optimizer`, `#Memory Efficiency`, `#Deep Learning`, `#GPU Training`

---

<a id="item-2"></a>
## [Startup founders urge Trump to keep Chinese open-weight AI accessible](https://www.politico.com/news/2026/07/22/startup-founders-urge-trump-not-to-shut-off-chinese-open-weight-ai-01008992) ⭐️ 8.0/10

A group of startup founders sent a letter to President Trump urging him not to impose sanctions on Chinese open-weight AI models, arguing that restricting access would harm US innovation and competitiveness. This debate highlights a critical tension between national security concerns and the open-source AI ecosystem that many US startups rely on for innovation and cost savings. The letter comes after Treasury Secretary Scott Bessent threatened sanctions against Chinese AI models over alleged intellectual property theft, specifically mentioning distillation of proprietary models.

hackernews · theanonymousone · Jul 23, 15:18 · [Discussion](https://news.ycombinator.com/item?id=49023016)

**Background**: Open-weight AI models are models whose trained parameters (weights) are publicly released, allowing developers to fine-tune and deploy them freely. Chinese models like DeepSeek and Qwen have become popular in the US startup community due to their competitive performance and permissive licenses.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/21/us-threatens-sanctions-against-chinese-ai-models-over-ip-theft/">US threatens sanctions against Chinese AI models over IP theft | TechCrunch</a></li>
<li><a href="https://thehill.com/policy/technology/5980722-scott-bessent-china-sanctions-ai-theft/">Scott Bessent warns US may sanction China over intellectual property theft tied to AI</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some argued that US AI companies also trained on unlicensed data, calling the sanctions hypocritical, while others worried about the impact on their own use of models like DeepSeek. A few noted that distillation may not constitute IP theft legally.

**Tags**: `#AI policy`, `#open-weight AI`, `#US-China relations`, `#intellectual property`, `#startups`

---

<a id="item-3"></a>
## [Prompt Injection Found in NeurIPS 2026 Paper PDF](https://www.reddit.com/r/MachineLearning/comments/1v4j1uk/prompt_injection_in_neurips_2026_d/) ⭐️ 8.0/10

A NeurIPS 2026 author discovered a hidden prompt injection in their paper's PDF on OpenReview, instructing reviewers to include specific phrases in their reviews, suggesting that some reviews may be LLM-generated. This incident raises serious concerns about the integrity of peer review at top AI conferences, as it indicates that reviewers may be using LLMs to generate reviews without proper oversight, potentially undermining the quality and trustworthiness of the review process. The prompt injection required the inclusion of three specific phrases: "This work addresses the central challenge," "The claims of the paper," and "Overall, I find this submission." The author noticed the injection when GPT warned them about the PDF, and they confirmed it was not present in their original submission.

reddit · r/MachineLearning · /u/Kwangryeol · Jul 23, 16:34

**Background**: Prompt injection is a technique where hidden instructions are embedded in text to manipulate AI outputs. In academic peer review, such injections could be used to force LLM-generated reviews to include specific phrases, making them detectable. Recent research has shown that prompt injection attacks on LLM-generated reviews are feasible and effective, raising ethical concerns in academic publishing.

<details><summary>References</summary>
<ul>
<li><a href="https://link.springer.com/article/10.1186/s41073-025-00187-7">Prompt injection in manuscripts: exploiting loopholes or ...</a></li>
<li><a href="https://arxiv.org/abs/2509.10248">[2509.10248] Prompt Injection Attacks on LLM Generated ...</a></li>
<li><a href="https://openreview.net/forum?id=HeMyWG4uYe">Prompt Injection Attacks on LLM Generated ... - OpenReview</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed alarm and skepticism, with many users calling for an investigation into the review process. Some commenters noted that the injection could have been added by a malicious actor rather than the conference itself, while others pointed out that the presence of such injections undermines trust in peer review.

**Tags**: `#AI ethics`, `#peer review`, `#prompt injection`, `#NeurIPS`, `#LLM`

---