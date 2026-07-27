---
layout: default
title: "Horizon Summary: 2026-07-27 (EN)"
date: 2026-07-27
lang: en
---

> From 52 items, 9 important content pieces were selected

---

1. [Moonshot AI Releases 3T Parameter MoE Model Kimi-K3](#item-1) ⭐️ 9.0/10
2. [Pyridoxal photoenzymes enable asymmetric radical cross-couplings](#item-2) ⭐️ 9.0/10
3. [Phase-homogeneous mixed halide perovskites boost tandem solar cell stability](#item-3) ⭐️ 9.0/10
4. [PGSimCity Visualizes PostgreSQL Internals Like a City](#item-4) ⭐️ 8.0/10
5. [Bun's Rust Rewrite Ships in Claude Code, v1.4 Delayed](#item-5) ⭐️ 8.0/10
6. [Mathematicians Urged to Prevent AI Harm to Mathematics](#item-6) ⭐️ 8.0/10
7. [Brain organoid computers overlook donor consent ethics](#item-7) ⭐️ 8.0/10
8. [UK physics facilities face closure without funding](#item-8) ⭐️ 7.0/10
9. [Evolutionary biology guides fever treatment decisions](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Moonshot AI Releases 3T Parameter MoE Model Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) ⭐️ 9.0/10

Moonshot AI has released Kimi-K3, a 3-trillion parameter Mixture-of-Experts (MoE) model, on HuggingFace with native mxfp4 quantization. The model is also available for inference via Fireworks AI at $3.00/M input tokens and $15.00/M output tokens. This release provides a rare public benchmark for serving costs of a 3-trillion parameter model, offering insights into the economics of large-scale AI inference. It also intensifies competition in the open-weight LLM space, potentially driving down prices for high-capability models. The model uses Kimi Delta Attention (KDA) and Attention Residuals (AttnRes) to improve information flow across long sequences and deep layers, and activates 16 out of 896 experts per token. Due to its 1.5 TB VRAM requirement in mxfp4, hosting realistically needs 16x B200 GPUs for context and throughput optimization.

hackernews · nateb2022 · Jul 27, 06:18 · [Discussion](https://news.ycombinator.com/item?id=49065752)

**Background**: Mixture-of-Experts (MoE) is a neural network architecture where only a subset of parameters (experts) are activated per input, enabling models with trillions of parameters while keeping computational costs manageable. Native mxfp4 quantization reduces memory footprint by storing weights in 4-bit floating point format. The model's license includes a revenue-based clause requiring a separate agreement for commercial use if aggregate revenue exceeds $20 million over 12 months.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K3 Tech Blog: Open Frontier Intelligence</a></li>

</ul>
</details>

**Discussion**: Commenters are analyzing the hosting costs, noting that the model requires ~1.5 TB VRAM and likely 16x B200 GPUs, making it expensive to serve. Some compare pricing trends, observing that competition has already driven down prices for similar models like GLM 5.2 by 45% in 1.5 months. There is also discussion about the lack of prosumer hardware with high VRAM and reasonable power consumption.

**Tags**: `#AI`, `#LLM`, `#MoE`, `#HuggingFace`, `#model release`

---

<a id="item-2"></a>
## [Pyridoxal photoenzymes enable asymmetric radical cross-couplings](https://www.nature.com/articles/s41586-026-10930-9) ⭐️ 9.0/10

Researchers report the development of pyridoxal-based photoenzymes that catalyze highly enantioselective radical–radical cross-coupling reactions, a previously challenging transformation. The work was published in Nature on July 27, 2026. This breakthrough combines photocatalysis and enzyme engineering to achieve asymmetric radical cross-couplings, representing a paradigm shift in biocatalysis and synthetic chemistry. It opens new avenues for constructing chiral molecules with high precision, impacting pharmaceutical and materials science. The photoenzymes utilize pyridoxal 5'-phosphate (PLP) as a cofactor, leveraging its excited state quinonoid intermediate as a potent reductant. The reaction proceeds under visible light and achieves high enantioselectivity, overcoming the challenge of controlling stereochemistry in radical–radical couplings.

rss · Nature - Latest Research · Jul 27, 00:00

**Background**: Radical–radical cross-coupling reactions are powerful for forming carbon–carbon bonds but are difficult to control enantioselectively due to the high reactivity and short lifetimes of radicals. Traditional methods often rely on transition-metal catalysts or chiral auxiliaries. Photoenzymes combine the selectivity of enzymes with the energy of light, enabling new reaction pathways. Pyridoxal phosphate is a versatile cofactor in nature, primarily known for transamination and decarboxylation, but its photochemical properties have been underexplored.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10930-9">Pyridoxal photoenzymes for asymmetric radical–radical cross-couplings - Nature</a></li>

</ul>
</details>

**Tags**: `#biocatalysis`, `#photocatalysis`, `#asymmetric synthesis`, `#enzyme engineering`, `#radical chemistry`

---

<a id="item-3"></a>
## [Phase-homogeneous mixed halide perovskites boost tandem solar cell stability](https://www.nature.com/articles/s41586-026-10929-2) ⭐️ 9.0/10

Researchers led by Sargent published a Nature paper demonstrating phase-homogeneous mixed halide perovskites that significantly enhance the stability of tandem solar cells, addressing a critical barrier to commercial viability. This breakthrough directly tackles photoinduced phase segregation, a major degradation mechanism in mixed-halide perovskites, paving the way for stable and efficient tandem photovoltaics that could surpass the efficiency limits of single-junction silicon cells. The phase-homogeneous material prevents halide segregation under illumination, maintaining uniform composition and optoelectronic properties. The paper was published online in Nature on July 27, 2026 (doi:10.1038/s41586-026-10929-2).

rss · Nature - Latest Research · Jul 27, 00:00

**Background**: Mixed-halide perovskites are promising for tandem solar cells because their bandgap can be tuned by adjusting the halide composition. However, they suffer from photoinduced phase segregation, where light causes the halides to separate, degrading performance. Tandem cells stack two photovoltaic materials (e.g., perovskite on silicon) to absorb a broader spectrum of sunlight, achieving higher efficiencies than single-junction cells.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tandem_solar_cell">Tandem solar cell</a></li>
<li><a href="https://pubs.rsc.org/en/content/articlelanding/2020/ee/d0ee00788a">Preventing phase segregation in mixed - halide perovskites ...</a></li>

</ul>
</details>

**Tags**: `#perovskite`, `#photovoltaics`, `#tandem solar cells`, `#materials science`, `#stability`

---

<a id="item-4"></a>
## [PGSimCity Visualizes PostgreSQL Internals Like a City](https://nikolays.github.io/PGSimCity/) ⭐️ 8.0/10

PGSimCity is an interactive visualization tool that simulates PostgreSQL's internal processes, such as query parsing, scheduling, and execution, using a city metaphor. It was released as an open-source project on GitHub, aiming to make database internals more accessible. Understanding PostgreSQL internals is crucial for DBAs and developers to optimize performance, but traditional architecture diagrams can be abstract and hard to grasp. PGSimCity offers a novel, engaging way to visualize complex scheduling and process management, potentially lowering the learning curve for database internals. The tool uses a city simulation analogy where different buildings represent PostgreSQL components like the parser, planner, and executor, and moving vehicles represent processes or queries. However, early feedback indicates that the auto-play tour can be overwhelming, and users desire more interactivity, such as entering custom queries to trace their execution path.

hackernews · jonbaer · Jul 27, 00:19 · [Discussion](https://news.ycombinator.com/item?id=49063754)

**Background**: PostgreSQL uses a multi-process architecture where each connection is handled by a separate process, and background workers handle tasks like vacuuming and checkpoints. Understanding how queries flow through parsing, planning, and execution, and how the scheduler manages concurrent processes, is key to tuning database performance. PGSimCity aims to visualize these concepts in an intuitive way.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=Q56kljmIN14">PostgreSQL Internal Architecture Explained - YouTube</a></li>
<li><a href="https://www.linkedin.com/pulse/postgresql-internal-architecture-comprehensive-memory-roohbakhsh-d5yuf">PostgreSQL Internal Architecture : A Comprehensive Overview of...</a></li>
<li><a href="https://vibhorgupta.hashnode.dev/understanding-the-internal-architecture-of-postgresql">PostgreSQL Internal Architecture Explained</a></li>

</ul>
</details>

**Discussion**: The community response is largely positive, praising the innovative approach and open-source nature, with suggestions for improvement. Users like layoric and narmiouh request more interactivity and less auto-play noise, while Curtis_Guan sees potential for reuse in other domains like Kubernetes. Some find the visuals overwhelming and the narration verbose.

**Tags**: `#PostgreSQL`, `#visualization`, `#database internals`, `#educational tool`

---

<a id="item-5"></a>
## [Bun's Rust Rewrite Ships in Claude Code, v1.4 Delayed](https://lockwood.dev/ai/2026/07/27/how-is-the-bun-rewrite-in-rust-going.html) ⭐️ 8.0/10

Bun's Rust rewrite has been deployed in Claude Code for over a month, but the v1.4 release is delayed until promised Node.js compatibility improvements are met. This rewrite is a major technical shift for Bun, a popular JavaScript runtime, and its progress affects developers relying on Bun for speed and Node.js compatibility. The delay underscores the challenge of maintaining compatibility while rewriting core components. Bun creator Jarred stated that the Rust rewrite shipped in Claude Code with minimal notice, and v1.4 is blocked on a specific number of newly passing Node.js tests. The PRs to achieve that are ready but not yet merged, with a likely release next Tuesday.

hackernews · tomlockwood · Jul 27, 11:12 · [Discussion](https://news.ycombinator.com/item?id=49067854)

**Background**: Bun is a fast all-in-one JavaScript runtime written originally in Zig, designed as a drop-in replacement for Node.js. The decision to rewrite Bun in Rust was driven by performance and ecosystem considerations, and the project has been using LLMs like Claude to assist in the translation.

<details><summary>References</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/ bun : Incredibly fast JavaScript runtime , bundler...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some note the rewrite's quiet deployment in Claude Code, while others question the value of using LLMs for such a large translation. A comparison point mentions a Zig-based fork achieving sub-second build times by fixing original issues, suggesting the rewrite might not have been necessary.

**Tags**: `#Bun`, `#Rust`, `#JavaScript runtime`, `#rewrite`, `#Node.js compatibility`

---

<a id="item-6"></a>
## [Mathematicians Urged to Prevent AI Harm to Mathematics](https://www.nature.com/articles/d41586-026-02309-7) ⭐️ 8.0/10

A Nature opinion piece published on July 27, 2026, calls on mathematicians to urgently recognize and mitigate AI's threats to the field of mathematics. This article highlights a critical and timely issue: AI could undermine mathematical rigor, creativity, and trust, affecting research, education, and applications across science and technology. The piece is an opinion article from Nature, a reputable scientific journal, and does not provide specific technical details but urges swift action from the mathematical community.

rss · Nature - Latest Research · Jul 27, 00:00

**Background**: AI tools, such as large language models, are increasingly used in mathematical research for tasks like theorem proving and data analysis. However, concerns have been raised that over-reliance on AI could lead to errors, loss of intuition, and erosion of mathematical standards.

**Tags**: `#AI`, `#mathematics`, `#ethics`, `#research`, `#policy`

---

<a id="item-7"></a>
## [Brain organoid computers overlook donor consent ethics](https://www.nature.com/articles/d41586-026-02316-8) ⭐️ 8.0/10

Researchers developing biocomputers using brain organoids have failed to address the ethical issue of informed consent from tissue donors, as highlighted in a Nature article published July 27, 2026. This oversight could undermine public trust in organoid intelligence and biocomputing, potentially slowing progress in a field that promises to revolutionize AI and neuroscience. The article notes that tissue donors may be unaware their cells are used for biocomputers, and current consent forms rarely cover such applications. The field of organoid intelligence (OI) uses 3D brain cell cultures with brain-machine interfaces.

rss · Nature - Latest Research · Jul 27, 00:00

**Background**: Organoid intelligence (OI) is an emerging field that grows 3D clusters of human brain cells (brain organoids) and connects them to computers via microelectrode arrays. These 'wetware' systems can perform learning tasks and may offer energy-efficient alternatives to silicon-based AI. However, ethical frameworks for using human neural tissue in computing have not kept pace with the technology.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Organoid_intelligence">Organoid intelligence</a></li>
<li><a href="https://en.wikipedia.org/wiki/Wetware_computer">Wetware computer - Wikipedia</a></li>
<li><a href="https://www.frontiersin.org/journals/science/articles/10.3389/fsci.2023.1017235/full">Frontiers | Organoid intelligence (OI): the new frontier in biocomputing and intelligence-in-a-dish</a></li>

</ul>
</details>

**Tags**: `#bioethics`, `#organoid intelligence`, `#biocomputing`, `#AI ethics`, `#neuroscience`

---

<a id="item-8"></a>
## [UK physics facilities face closure without funding](https://www.nature.com/articles/d41586-026-02171-7) ⭐️ 7.0/10

A Nature article reports that the UK's national synchrotron, a laser facility, and a particle accelerator are at risk of closure unless funding is secured. These facilities are critical for UK and international scientific research, and their closure would severely impact materials science, biology, and physics research. The facilities mentioned include Diamond Light Source (the UK's national synchrotron), the Central Laser Facility, and a particle accelerator such as VELA.

rss · Nature - Latest Research · Jul 27, 00:00

**Background**: Diamond Light Source is the UK's national synchrotron science facility, located at Harwell Campus in Oxfordshire. It is 86% owned by the UK government and provides intense X-ray beams for research. The Central Laser Facility and particle accelerators like VELA support a wide range of scientific and industrial applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Diamond_Light_Source">Diamond Light Source - Wikipedia</a></li>
<li><a href="https://www.diamond.ac.uk/Home/About/FAQs/About-Synchrotrons.html">About Synchrotrons - - Diamond Light Source</a></li>
<li><a href="https://www.interactions.org/press-release/new-uk-particle-accelerator-heralds-exciting-opportunities">New UK particle accelerator heralds exciting opportunities for industry</a></li>

</ul>
</details>

**Tags**: `#physics`, `#science policy`, `#UK research`, `#funding`

---

<a id="item-9"></a>
## [Evolutionary biology guides fever treatment decisions](https://www.nature.com/articles/d41586-026-02313-x) ⭐️ 6.0/10

A Nature article argues that understanding natural selection can improve medical treatments, using fever as an example to question when to treat it. This perspective could shift clinical guidelines by integrating evolutionary principles, potentially reducing unnecessary treatments and antibiotic resistance. The article was published online on 27 July 2026 in Nature, with a doi:10.1038/d41586-026-02313-x.

rss · Nature - Latest Research · Jul 27, 00:00

**Background**: Fever is an evolutionary adaptation that helps fight infection, but modern medicine often suppresses it. The article suggests that evolutionary biology can inform when fever is beneficial versus harmful.

**Tags**: `#evolutionary biology`, `#medicine`, `#science`

---