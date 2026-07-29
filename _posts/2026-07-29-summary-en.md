---
layout: default
title: "Horizon Summary: 2026-07-29 (EN)"
date: 2026-07-29
lang: en
---

> From 117 items, 10 important content pieces were selected

---

1. [TurboFieldfare runs Gemma 4 26B in 2GB RAM on M-series Macs](#item-1) ⭐️ 9.0/10
2. [AI worms self-propagate through Copilot for Word](#item-2) ⭐️ 9.0/10
3. [Piezochiral Effect Discovered: Strain Controls Chirality](#item-3) ⭐️ 9.0/10
4. [Bacteria use STAND NTPases to detect diverse phage proteins](#item-4) ⭐️ 9.0/10
5. [CO2 and bicycloalkane copolymerization yields recyclable polyesters](#item-5) ⭐️ 9.0/10
6. [Avalanche-like lithium dynamics in graphite observed](#item-6) ⭐️ 9.0/10
7. [Nanopore 'chop and measure' sequences peptides at single-amino-acid resolution](#item-7) ⭐️ 9.0/10
8. [Weight-four parity checks in a spin-shuttling architecture](#item-8) ⭐️ 9.0/10
9. [Digitally Controlled Silicon Quantum Processing Unit Demonstrated](#item-9) ⭐️ 9.0/10
10. [KOReader: Open-Source E-Reader App with Mixed Reviews](#item-10) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [TurboFieldfare runs Gemma 4 26B in 2GB RAM on M-series Macs](https://github.com/drumih/turbo-fieldfare) ⭐️ 9.0/10

TurboFieldfare, an open-source inference engine written in Swift and Metal, enables running the 4-bit quantized Gemma 4 26B-A4B-IT model on any M-series Mac with only 2 GB of RAM by streaming routed experts from SSD. This technique dramatically lowers the memory barrier for running large MoE models on consumer hardware, potentially enabling powerful on-device AI on memory-constrained Macs and future devices. The model's 4-bit quantized weights are about 14 GB, but TurboFieldfare keeps only the shared layers and KV cache in RAM (≈2 GB) and streams routed experts from SSD on demand, achieving 5–6 tok/s on an M2 MacBook Air and 31–35 tok/s on an M5 MacBook Pro.

hackernews · gitpusher42 · Jul 29, 15:05 · [Discussion](https://news.ycombinator.com/item?id=49098510)

**Background**: Gemma 4 26B-A4B-IT is a Mixture-of-Experts (MoE) model from Google DeepMind with 25.2B total parameters but only 3.8B active per token, making it efficient yet powerful. Traditional inference engines require loading all weights into RAM, which is prohibitive for large models on devices with limited memory. TurboFieldfare exploits the MoE architecture's sparsity by storing expert weights on SSD and loading only the needed experts for each token, overlapping I/O with computation.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/google/gemma-4-26B-A4B-it/tree/main">google/ gemma - 4 - 26 B - A 4 B - it at main</a></li>
<li><a href="https://openrouter.ai/google/gemma-4-26b-a4b-it:free">Gemma 4 26 B A 4 B (free) - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://gemma4.com/">Gemma 4 — Google DeepMind</a></li>

</ul>
</details>

**Discussion**: Commenters noted that llama.cpp with mmap can also run large models with limited RAM, but TurboFieldfare's explicit synchronization of SSD reads with inference may reduce latency. Users reported successful compilation on older macOS versions and expressed excitement about future hardware generations enabling practical local inference.

**Tags**: `#on-device AI`, `#inference engine`, `#model quantization`, `#Swift/Metal`, `#Mac`

---

<a id="item-2"></a>
## [AI worms self-propagate through Copilot for Word](https://enklypesalt.com/posts/context-collapse-part3-ai-worming-through-word/) ⭐️ 9.0/10

Researchers demonstrated document-borne AI worms that can self-propagate through Microsoft Copilot for Word, exploiting the inability of AI systems to distinguish instructions from data. This research highlights a critical vulnerability class with no current mitigations, potentially allowing malicious instructions hidden in documents to alter content and propagate attacks across systems. The attack uses prompt injection to embed adversarial instructions in documents, which Copilot then executes as legitimate commands, enabling the worm to spread to new documents.

hackernews · Canopy9560 · Jul 29, 11:44 · [Discussion](https://news.ycombinator.com/item?id=49096188)

**Background**: Prompt injection is a cybersecurity exploit where innocuous-looking inputs cause unintended behavior in large language models (LLMs). LLMs with capabilities like web browsing or file access can be targeted by indirect prompt injection, where adversarial prompts are embedded in content the model retrieves. In this case, the AI assistant treats document content as part of its conversational context, making it vulnerable to embedded instructions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://asibiont.com/en/blog/document-borne-ai-worms-kak-novyy-cherv-porazhaet-copilot-dlya-word-i-samorasprostranyaetsya">Document-Borne AI Worms : How Self - Propagating ... — ASI Biont Blog</a></li>
<li><a href="https://penaxtra.com/blog/self-propagating-ai-worm-what-it-means">The Self - Propagating AI Worm : Separating the Signal... | Penaxtra Blog</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern that this vulnerability is fundamentally unfixable as long as AI systems mix instructions with data. Some noted that granting extensive access to AI agents increases risk, and one user described the worms as analogous to memes propagating ideas.

**Tags**: `#AI security`, `#adversarial attacks`, `#prompt injection`, `#Copilot`, `#vulnerability`

---

<a id="item-3"></a>
## [Piezochiral Effect Discovered: Strain Controls Chirality](https://www.nature.com/articles/s41586-026-10845-5) ⭐️ 9.0/10

Researchers have discovered the piezochiral effect, a new physical phenomenon that allows mechanical strain to directly control the chirality of materials, as reported in Nature on July 29, 2026. This discovery adds a new fundamental effect to the family of strain-responsive functionalities, alongside piezoelectricity and piezomagnetism, with potential applications in photonics, spintronics, biosensing, and quantum information. The piezochiral effect enables linear coupling between mechanical strain and chirality, a structural order parameter that was previously difficult to control directly. The work was published in Nature and also appeared on arXiv (2510.21674) in October 2025.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: Chirality refers to the property of an object being non-superimposable on its mirror image, like left and right hands. In materials science, controlling chirality is important for applications such as nonlinear optics and spintronics. Piezoelectricity and piezomagnetism are well-known effects where strain induces electric or magnetic polarization, but a direct strain-chirality coupling had not been demonstrated until now.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Piezoelectricity">Piezoelectricity - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2510.21674">[2510.21674] The Piezochiral Effect</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chirality_(chemistry)">Chirality (chemistry) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#physics`, `#materials science`, `#chirality`, `#piezoelectricity`, `#quantum information`

---

<a id="item-4"></a>
## [Bacteria use STAND NTPases to detect diverse phage proteins](https://www.nature.com/articles/s41586-026-10852-6) ⭐️ 9.0/10

A systematic analysis published in Nature reveals that bacterial STAND NTPases, relatives of animal immune receptors, can detect a wide range of core structural and replicative proteins from bacteriophages, analogous to pattern recognition in animal immunity. This discovery uncovers a broad antiviral sensing mechanism in bacteria, potentially reshaping our understanding of prokaryotic immunity and inspiring new biotechnological applications, such as engineered bacterial defenses against phages. The study systematically analyzed prokaryotic STAND NTPases and found that they recognize most core phage proteins, including structural and replicative components, suggesting a convergent evolution with animal immune systems.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: STAND (Signal Transduction ATPases with Numerous Domains) NTPases are a class of P-loop NTPases found in bacteria, plants, and animals, often involved in immune signaling. In animals, pattern recognition receptors (PRRs) detect conserved pathogen molecules; this study shows bacteria use similar STAND NTPases to sense phage core proteins, highlighting an ancient immune strategy.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0022283604010010">STAND, a Class of P-Loop NTPases Including Animal and Plant ...</a></li>

</ul>
</details>

**Tags**: `#bacteriophage`, `#immunity`, `#microbiology`, `#structural biology`, `#Nature`

---

<a id="item-5"></a>
## [CO2 and bicycloalkane copolymerization yields recyclable polyesters](https://www.nature.com/articles/s41586-026-10848-2) ⭐️ 9.0/10

Researchers report a simple organic catalyst that enables direct alternating copolymerization of CO2 with bicycloalkanes to produce high-performance polyesters, which can be selectively depolymerized and recycled in a closed-loop lifecycle. The study was published in Nature on July 29, 2026. This breakthrough addresses two major challenges: utilizing CO2 as a renewable feedstock and creating truly circular plastics. It offers a sustainable pathway to high-performance polyesters that can be chemically recycled, reducing reliance on fossil fuels and mitigating plastic waste. The catalyst is a simple organic compound, avoiding toxic metals, and the alternating copolymerization ensures precise monomer sequencing. The resulting polyesters exhibit high performance and can be selectively depolymerized back to monomers for closed-loop recycling.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: Copolymers consist of two or more different monomers arranged along a polymer chain. Alternating copolymers have a regular alternating sequence of monomers, which can impart unique properties. CO2 copolymerization with epoxides has been studied, but using bicycloalkanes as comonomers is novel. Bicycloalkanes are hydrocarbons with two fused rings, offering rigidity and potential for high-performance materials.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Copolymer">Copolymer - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Category:Bicycloalkanes">Category:Bicycloalkanes - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#CO2 utilization`, `#polymer chemistry`, `#circular economy`, `#sustainable materials`, `#catalysis`

---

<a id="item-6"></a>
## [Avalanche-like lithium dynamics in graphite observed](https://www.nature.com/articles/s41586-026-10862-4) ⭐️ 9.0/10

Researchers used operando optical microscopy to directly observe avalanche-like lithium deintercalation and intercalation processes in graphite electrodes, revealing how local disorder governs phase-transition dynamics. This discovery provides fundamental insights into lithium-ion battery performance and degradation, potentially leading to improved battery design and longer lifespan. The study, published in Nature on July 29, 2026, focuses on dilute stages of graphite during emptying and filling, showing that disorder at the local scale triggers avalanche-like phase transitions.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: Graphite is the most common anode material in lithium-ion batteries, where lithium ions intercalate between graphene layers. Phase transitions during intercalation/deintercalation affect battery rate capability and cycle life. Operando optical microscopy allows real-time visualization of these processes at the microscale.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/operando-optical-microscopy">Operando Optical Microscopy - emergentmind.com</a></li>

</ul>
</details>

**Tags**: `#lithium-ion batteries`, `#graphite`, `#phase transitions`, `#operando microscopy`, `#energy storage`

---

<a id="item-7"></a>
## [Nanopore 'chop and measure' sequences peptides at single-amino-acid resolution](https://www.nature.com/articles/s41586-026-10881-1) ⭐️ 9.0/10

Researchers have developed a nanopore-based method that sequences peptides at single-amino-acid resolution by using enzymatic digestion to progressively shorten the N-terminus one residue at a time, combined with repetitive N-terminus re-reading. The work was published in Nature on July 29, 2026. This breakthrough could revolutionize proteomics by enabling single-molecule protein sequencing, which has been a long-standing challenge. It may lead to new insights into protein function, disease mechanisms, and personalized medicine. The method, termed 'chop and measure', uses a nanopore to read the peptide sequence as each amino acid is cleaved from the N-terminus by an enzyme. The repetitive re-reading of the N-terminus ensures accurate identification of each residue.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: Nanopore sequencing has been successfully applied to DNA and RNA, but protein sequencing at single-amino-acid resolution has remained elusive due to the complexity of amino acid chemistry and the lack of a processive enzyme. This work overcomes these hurdles by using a stepwise enzymatic digestion approach that shortens the peptide one residue at a time, allowing the nanopore to read the sequence as it is shortened.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10881-1">Sequential reading of a stepwise-shortened peptide ... - Nature</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12006967/">Toward single-molecule protein sequencing using nanopores - PMC</a></li>

</ul>
</details>

**Tags**: `#nanopore`, `#peptide sequencing`, `#proteomics`, `#single-molecule`, `#biotechnology`

---

<a id="item-8"></a>
## [Weight-four parity checks in a spin-shuttling architecture](https://www.nature.com/articles/s41586-026-10766-3) ⭐️ 9.0/10

Researchers demonstrated weight-four parity checks using a silicon spin-qubit device with a shuttling bus for qubit transport, as published in Nature on July 29, 2026. This work shows that shuttling is a viable method for scaling up semiconductor quantum processors, enabling the high-fidelity multi-qubit parity measurements essential for fault-tolerant quantum computing. The device achieved parity checks up to weight four, meaning it can measure the parity of up to four data qubits simultaneously, which is a key requirement for surface code error correction.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: Spin qubits in silicon are a promising platform for quantum computing due to their small size and long coherence times. However, scaling up requires the ability to move qubits across the chip (shuttling) and perform multi-qubit parity measurements for error correction. Weight-four parity checks are particularly important for the surface code, a leading quantum error correction scheme.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2601.23267v1">Weight - four parity checks with silicon spin qubits</a></li>
<li><a href="https://link.aps.org/doi/10.1103/PRXQuantum.5.020353">High-Fidelity Spin Qubit Shuttling via Large Spin-Orbit ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#spin qubits`, `#semiconductor`, `#parity checks`, `#Nature`

---

<a id="item-9"></a>
## [Digitally Controlled Silicon Quantum Processing Unit Demonstrated](https://www.nature.com/articles/s41586-026-10754-7) ⭐️ 9.0/10

Researchers have demonstrated a silicon quantum processing unit that executes high-fidelity multiqubit circuits using a digitally programmed cryogenic CMOS controller and a high-density superconducting ribbon cable. This work represents a major step toward scalable quantum computing by integrating cryogenic control electronics with silicon qubits, addressing a key engineering challenge in building practical quantum processors. The controller generates all time-varying control signals digitally and delivers them to the exchange-only qubit device via a superconducting ribbon cable, achieving high-fidelity multiqubit operations.

rss · Nature - Latest Research · Jul 29, 00:00

**Background**: Silicon qubits are promising for quantum computing due to their long coherence times and compatibility with semiconductor manufacturing. However, scaling up requires precise control electronics that operate at cryogenic temperatures. Cryogenic CMOS controllers can generate the necessary signals while minimizing heat load and wiring complexity.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2302.11538">Using Cryogenic CMOS Control Electronics To Enable A Two–Qubit</a></li>
<li><a href="https://arxiv.org/abs/1005.0273">[1005.0273] Coherent spin manipulation in an exchange-only qubit</a></li>
<li><a href="https://arxiv.org/pdf/2306.13574">Improved Flexible Coaxial Ribbon Cable for High-Density ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#silicon qubits`, `#cryogenic CMOS`, `#Nature publication`

---

<a id="item-10"></a>
## [KOReader: Open-Source E-Reader App with Mixed Reviews](https://koreader.rocks/) ⭐️ 7.0/10

KOReader is an open-source document viewer for E Ink devices that supports a wide range of file formats including EPUB, PDF, DjVu, and MOBI, and runs on Kindle, Kobo, PocketBook, Android, and desktop Linux. KOReader significantly enhances the reading experience on proprietary e-readers by offering advanced features and customization, but its non-intuitive UI and occasional lag have drawn criticism, highlighting the trade-offs between open-source flexibility and user-friendliness. The application supports multiple file formats and devices, but users report issues with UI intuitiveness, lag, and gesture responsiveness. A Zen UI plugin is recommended to improve the experience.

hackernews · Cider9986 · Jul 29, 11:05 · [Discussion](https://news.ycombinator.com/item?id=49095865)

**Background**: E-readers like Kindle and Kobo typically use proprietary software that limits file format support and customization. KOReader is an open-source alternative that can be installed on jailbroken devices, offering features like native EPUB and PDF support, reflow, and Calibre integration.

<details><summary>References</summary>
<ul>
<li><a href="http://koreader.rocks/">KOReader</a></li>
<li><a href="https://github.com/koreader/koreader">GitHub - koreader / koreader : An ebook reader application...</a></li>
<li><a href="https://www.reddit.com/r/koreader/">KOReader: the open-source multi-format and multi-platform ...</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users praise KOReader for fundamentally improving their reading experience and driving purchasing decisions, while others criticize its non-intuitive UI and lag, comparing it to GIMP. A user noted that the Zen UI plugin is essential for a good experience.

**Tags**: `#open-source`, `#e-reader`, `#software`, `#UI/UX`, `#community`

---