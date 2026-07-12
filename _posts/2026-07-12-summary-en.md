---
layout: default
title: "Horizon Summary: 2026-07-12 (EN)"
date: 2026-07-12
lang: en
---

> From 40 items, 3 important content pieces were selected

---

1. [Terry Tao Uses AI Coding Agents to Build Math Visualizations](#item-1) ⭐️ 9.0/10
2. [Mesh LLM: Distributed AI Computing on iroh](#item-2) ⭐️ 8.0/10
3. [Circular Financing in GPU Boom: Nvidia, CoreWeave, Nebius](#item-3) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Terry Tao Uses AI Coding Agents to Build Math Visualizations](https://terrytao.wordpress.com/2026/07/11/old-and-new-apps-via-modern-coding-agents/) ⭐️ 9.0/10

Fields Medalist Terry Tao demonstrated using modern LLM-based coding agents to create interactive visualizations for mathematical papers, highlighting the vast latent demand for software outside traditional domains. This signals a paradigm shift in how even top mathematicians approach tool-building, potentially accelerating research and making complex concepts more accessible. It also underscores the transformative impact of AI-assisted programming across all disciplines. Tao noted that while LLM-coded supplements are not mission-critical to the core paper, the downside risk of using guided interaction with LLM agents for such visualizations is acceptable. The post received high engagement (255 points, 66 comments) on Hacker News.

hackernews · subset · Jul 12, 11:09 · [Discussion](https://news.ycombinator.com/item?id=48880170)

**Background**: Coding agents are AI systems that assist in writing software, often using large language models (LLMs) to generate code from natural language prompts. Terry Tao is a renowned mathematician and Fields Medalist, and his endorsement of these tools carries significant weight in both mathematics and software communities.

**Discussion**: Commenters expressed excitement about the potential of LLMs for visualization in education and research, with one noting that even if LLMs stopped improving today, it would take years to catch up to the new capabilities. Others humorously compared Tao's use of coding agents to a Michelin-starred chef discovering microwave dinners.

**Tags**: `#LLM`, `#coding agents`, `#mathematics`, `#software development`, `#AI-assisted programming`

---

<a id="item-2"></a>
## [Mesh LLM: Distributed AI Computing on iroh](https://www.iroh.computer/blog/mesh-llm) ⭐️ 8.0/10

Mesh LLM is a new open-source tool that enables distributed AI inference by pooling VRAM across multiple peers over a peer-to-peer network built on iroh. Users can run larger language models than their local hardware supports with a simple command like 'mesh-llm --auto'. This approach democratizes access to large language models by allowing individuals to pool their consumer-grade GPUs, potentially reducing the need for expensive dedicated hardware. It also showcases a practical application of peer-to-peer networking for AI workloads, which could inspire further innovation in distributed machine learning. Mesh LLM uses the iroh library for peer-to-peer communication, which relies on public key-based addressing and BLAKE3 content-addressed blob transfer. The project is experimental and currently lacks comprehensive performance benchmarks, but early tests show Qwen 235B A22B achieving 16 tokens per second across two nodes.

hackernews · tionis · Jul 11, 22:38 · [Discussion](https://news.ycombinator.com/item?id=48876505)

**Background**: Large language models (LLMs) require significant GPU memory (VRAM) to run, often exceeding what a single consumer GPU can provide. Traditional approaches to run larger models include model quantization, offloading to system RAM, or using specialized multi-GPU hardware with high-speed interconnects like NVLink. Mesh LLM takes a different approach by distributing model layers across multiple machines over a network, effectively pooling their VRAM.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/n0-computer/iroh">GitHub - n0-computer/ iroh : IP addresses break, dial keys instead.</a></li>
<li><a href="https://github.com/Mesh-LLM/mesh-llm">GitHub - Mesh - LLM / mesh - llm : Distributed AI/ LLM for the people.</a></li>
<li><a href="https://meshllm.cloud/">Mesh LLM</a></li>

</ul>
</details>

**Discussion**: Community feedback is overwhelmingly positive, with users reporting that the tool 'worked first try' and praising its ease of use. However, some commenters raised concerns about performance over consumer networks, questioning whether the latency would be acceptable for real-time inference. A contributor clarified that the project is experimental and encouraged further testing.

**Tags**: `#distributed computing`, `#LLM`, `#P2P`, `#AI infrastructure`, `#open source`

---

<a id="item-3"></a>
## [Circular Financing in GPU Boom: Nvidia, CoreWeave, Nebius](https://io-fund.com/ai-stocks/nvidia-coreweave-nebius-circular-financing-gpu-boom) ⭐️ 8.0/10

An analysis reveals that Nvidia, CoreWeave, and Nebius are engaged in a circular financing model where Nvidia invests in and supplies GPUs to these AI cloud providers, who then use the GPUs as collateral to secure more funding for further GPU purchases from Nvidia. This circular financing raises questions about the sustainability of massive capital expenditures in AI infrastructure, as the profitability of these builds depends on high utilization and future demand for GPU compute, which may not materialize as expected. Nvidia invested $2 billion for a 9% equity stake in CoreWeave, which plans $35 billion in CapEx in 2026, meaning Nvidia's investment covers only 5.7% of that year's spending. The rest comes from other sources, but the circularity lies in GPUs being used as collateral for loans that fund more GPU purchases.

hackernews · adletbalzhanov · Jul 11, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48873836)

**Background**: Circular financing refers to a model where a company invests in its customers, who then use the proceeds to buy the company's products, creating a self-reinforcing cycle. In the GPU boom, Nvidia invests in AI cloud providers like CoreWeave and Nebius, which then use Nvidia GPUs as collateral to secure debt financing for further GPU purchases. This model has fueled rapid expansion but raises concerns about overbuilding and financial risk if demand for GPU compute slows.

<details><summary>References</summary>
<ul>
<li><a href="https://io-fund.com/ai-stocks/nvidia-coreweave-nebius-circular-financing-gpu-boom">Nvidia, CoreWeave, and Nebius: Inside the Circular Financing ...</a></li>
<li><a href="https://theentrepreneurstory.com/articles/long-reads/the-gpu-boom-circular-financing-ai-infrastructure">The GPU Boom: Circular Financing in AI Infrastructure *Nvidia ...</a></li>
<li><a href="https://leadermenu.com/lead-the-business/nvidia-coreweave-and-nebius-inside-the-circular-financing-of-the-gpu-boom/">Nvidia, CoreWeave, And Nebius: Inside The Circular Financing ...</a></li>

</ul>
</details>

**Discussion**: Commenters debate whether the circular financing is a significant issue, with some arguing Nvidia's investment is a small fraction of CoreWeave's total CapEx. Others focus on the path to profitability, suggesting metrics like ROI per token and enterprise token budgets are more important. There is also skepticism about the sustainability of the model and concerns about overbuild relative to token ROI.

**Tags**: `#GPU`, `#financing`, `#Nvidia`, `#cloud computing`, `#AI infrastructure`

---