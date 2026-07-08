---
layout: default
title: "Horizon Summary: 2026-07-08 (EN)"
date: 2026-07-08
lang: en
---

> From 102 items, 10 important content pieces were selected

---

1. [Tenda Firmware Backdoor Allows Unauthorized Admin Access](#item-1) ⭐️ 9.0/10
2. [Floquet Rotational Superradiance Observed in Ring Resonators](#item-2) ⭐️ 9.0/10
3. [Humanoid Robots Perform Laparoscopic Surgery in Feasibility Study](#item-3) ⭐️ 9.0/10
4. [Novel electrolyte design stabilizes lithium metal batteries](#item-4) ⭐️ 9.0/10
5. [Epitope Editing Enables Non-Genotoxic Stem Cell Transplant](#item-5) ⭐️ 9.0/10
6. [Reinforcement learning boosts quantum error correction](#item-6) ⭐️ 9.0/10
7. [Cosmic protons enable space treaty verification](#item-7) ⭐️ 9.0/10
8. [Universal cell embedding foundation model trained on 36 million cells](#item-8) ⭐️ 9.0/10
9. [Mistral Unveils Robostral Navigate for Map-Less Robot Navigation](#item-9) ⭐️ 8.0/10
10. [GitLost: Prompt Injection Leaks Private Repos via GitHub AI Agent](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Tenda Firmware Backdoor Allows Unauthorized Admin Access](https://kb.cert.org/vuls/id/213560) ⭐️ 9.0/10

Multiple versions of Tenda firmware contain a hidden authentication backdoor (CVE-2026-11405) that uses a hardcoded password to bypass login and grant full administrative control over routers and other devices. This vulnerability exposes millions of Tenda devices to remote takeover, enabling attackers to monitor traffic, launch further attacks, or add devices to botnets. It underscores the systemic security failures in IoT firmware and erodes consumer trust in networking hardware vendors. The backdoor password is "rzadmin" and the username is not validated, so any username works. The vulnerability affects multiple Tenda firmware versions and has not been patched despite prior disclosure in 2022.

hackernews · miniBill · Jul 8, 00:08 · [Discussion](https://news.ycombinator.com/item?id=48825749)

**Background**: Hardcoded passwords are credentials embedded in device firmware that cannot be changed by users. In IoT devices, such passwords are often discovered through reverse engineering of firmware images, as seen in the Mirai botnet attacks. This backdoor is particularly dangerous because it provides administrative access without requiring valid credentials.

<details><summary>References</summary>
<ul>
<li><a href="https://kb.cert.org/vuls/id/213560">Tenda firmware (multiple versions) contains hidden authentication backdoor</a></li>
<li><a href="https://thehackernews.com/2026/07/certcc-warns-of-hidden-admin-backdoor.html">CERT/CC Warns of Hidden Admin Backdoor in Tenda Router Firmware</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/cyber-security/hidden-backdoor-found-in-tenda-routers-goes-unpatched-despite-warnings-from-cybersecurity-researchers-affected-firmware-allows-admin-access-without-a-password">Hidden backdoor found in Tenda routers goes unpatched despite warnings ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration with the prevalence of such backdoors, with one user noting that the password "rzadmin" was disclosed in a 2022 writeup. Another user recommended installing OpenWRT on any router to avoid vendor firmware, while others highlighted the irony of amateur-level security flaws in networking hardware.

**Tags**: `#security`, `#backdoor`, `#firmware`, `#IoT`, `#vulnerability`

---

<a id="item-2"></a>
## [Floquet Rotational Superradiance Observed in Ring Resonators](https://www.nature.com/articles/s41586-026-10725-y) ⭐️ 9.0/10

Researchers have experimentally observed Floquet rotational superradiance in a spatiotemporally modulated ring network of resonators, as reported in Nature on July 8, 2026. This observation marks a significant breakthrough in quantum optics and condensed matter physics, demonstrating a new regime of light-matter interaction that could enable advances in quantum technologies and synthetic frequency dimensions. The experiment utilized a spatiotemporally modulated ring network of resonators to achieve Floquet rotational superradiance, a phenomenon where collective emission is enhanced by periodic driving. The work was published in Nature with doi:10.1038/s41586-026-10725-y.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: Superradiance is a collective emission effect where a group of emitters radiate coherently, resulting in an enhanced intensity proportional to the square of the number of emitters. Floquet physics involves periodic driving of a system, leading to novel phases and phenomena not present in static systems. Spatiotemporal modulation of resonators creates synthetic frequency dimensions, enabling control over light propagation and interactions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Superradiance">Superradiance - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2212.04898">[2212.04898] Floquet superradiance lattices in thermal atoms</a></li>
<li><a href="https://link.aps.org/doi/10.1103/PhysRevLett.129.273603">Floquet Superradiance Lattices in Thermal Atoms | Phys. Rev. Lett.</a></li>

</ul>
</details>

**Tags**: `#quantum optics`, `#super-radiance`, `#Floquet physics`, `#condensed matter`, `#experimental physics`

---

<a id="item-3"></a>
## [Humanoid Robots Perform Laparoscopic Surgery in Feasibility Study](https://www.nature.com/articles/s41586-026-10796-x) ⭐️ 9.0/10

A systematic evaluation published in Nature demonstrates that contemporary humanoid robots, such as the Unitree G1, can perform laparoscopic surgical tasks via teleoperation using the da Vinci Research Kit. This research shows that general-purpose humanoid robots could potentially replace specialized surgical systems like da Vinci, reducing costs and expanding access to robotic surgery. The teleoperation setup uses a G1 humanoid robot grasping commercially available laparoscopic instruments, controlled through the Master Tool Manipulators of the da Vinci Research Kit, highlighting key technical challenges before clinical deployment.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: Laparoscopic surgery is a minimally invasive technique using small incisions and specialized instruments. The da Vinci Surgical System is the current standard for robotic-assisted laparoscopy, but it is expensive and specialized. Humanoid robots offer a versatile alternative that could be adapted for multiple tasks in the operating room.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2510.03529">LapSurgie: Humanoid Robots Performing Surgery via Teleoperated Handheld Laparoscopy</a></li>
<li><a href="https://today.ucsd.edu/story/the-robot-will-see-you-now">The Robot Will See You Now - UC San Diego Today</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#surgery`, `#humanoid robots`, `#teleoperation`, `#medical technology`

---

<a id="item-4"></a>
## [Novel electrolyte design stabilizes lithium metal batteries](https://www.nature.com/articles/s41586-026-10732-z) ⭐️ 9.0/10

Researchers have developed a single-phase gradient-solvation electrolyte by incorporating a targeted ligand anti-solvent into an anion-rich ether-based electrolyte, achieving lithium metal batteries with long cycle life, high energy density, and high capacity retention. The study was published in Nature on July 8, 2026. This breakthrough addresses key challenges in lithium metal batteries, such as dendrite growth and low Coulombic efficiency, which have hindered their commercial adoption. The new electrolyte design could enable safer, longer-lasting batteries for electric vehicles and portable electronics. The targeted ligand anti-solvent modifies the solvation structure to create a gradient concentration of anions from the anode to the cathode, stabilizing the electrode-electrolyte interfaces. The electrolyte is single-phase and ether-based, avoiding the complexity of dual-solvent systems.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: Lithium metal batteries are promising for high energy density but suffer from unstable solid-electrolyte interphase and dendrite formation. Conventional electrolytes often use dual-solvent or highly concentrated systems to improve stability, but these approaches have limitations. The new design uses a targeted ligand anti-solvent to achieve gradient solvation in a single-phase electrolyte, offering a simpler and more effective solution.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41467-023-36647-1">Non-polar ether-based electrolyte solutions for stable high-voltage non-aqueous lithium metal batteries | Nature Communications</a></li>
<li><a href="https://www.nature.com/articles/s41467-025-57910-7">Anion-mediated approach to overcome oxidation in ether electrolytes for high-voltage sodium-ion batteries | Nature Communications</a></li>

</ul>
</details>

**Tags**: `#lithium metal batteries`, `#electrolyte`, `#energy storage`, `#Nature`

---

<a id="item-5"></a>
## [Epitope Editing Enables Non-Genotoxic Stem Cell Transplant](https://www.nature.com/articles/s41586-026-10737-8) ⭐️ 9.0/10

Researchers demonstrated that epitope editing of the KIT receptor allows antibody-based, non-genotoxic conditioning to selectively enrich therapeutic BCL11A-edited hematopoietic stem/progenitor cells, enhancing fetal hemoglobin induction for sickle cell disease and β-thalassemia. This approach eliminates the need for genotoxic conditioning agents like chemotherapy or radiation, potentially reducing side effects and broadening access to stem cell gene therapies for blood disorders. The study, published in Nature on July 8, 2026, shows that epitope-edited KIT enables durable engraftment and preserves clonal diversity of edited cells, with enhanced fetal hemoglobin induction.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: Hematopoietic stem cell transplantation often requires conditioning with genotoxic agents to make space for donor cells, which can cause severe side effects. Epitope editing modifies a protein's surface region so that specific antibodies can bind and selectively eliminate unedited cells, avoiding genotoxicity.

**Tags**: `#gene editing`, `#hematopoietic stem cells`, `#sickle cell disease`, `#β-thalassemia`, `#epitope editing`

---

<a id="item-6"></a>
## [Reinforcement learning boosts quantum error correction](https://www.nature.com/articles/s41586-026-10759-2) ⭐️ 9.0/10

Researchers have combined reinforcement learning with quantum error correction to enable continuous self-calibration during computation, achieving record low logical error rates. The work was published in Nature on July 8, 2026. This breakthrough significantly improves the resilience of quantum computers to drift and noise, bringing practical fault-tolerant quantum computing closer to reality. It demonstrates a powerful synergy between machine learning and quantum error correction. The reinforcement learning agent continuously adjusts error correction parameters in real time without interrupting computation. The method achieved record logical error rates, outperforming previous static calibration approaches.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: Quantum error correction (QEC) protects quantum information from errors caused by decoherence and noise. Traditional QEC relies on static calibration, which degrades over time due to hardware drift. Reinforcement learning offers a way to adaptively optimize error correction in response to changing conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quantum_error_correction">Quantum error correction</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#reinforcement learning`, `#error correction`, `#Nature`

---

<a id="item-7"></a>
## [Cosmic protons enable space treaty verification](https://www.nature.com/articles/s41586-026-10783-2) ⭐️ 9.0/10

Researchers have demonstrated that neutrons produced by cosmic proton spallation in the Van Allen radiation belts can be used to detect hidden thermonuclear weapons on satellites, as published in Nature on July 8, 2026. This technique provides a verifiable method to enforce the Outer Space Treaty, potentially preventing the weaponization of space and enhancing global security. A shoebox-sized detector satellite could identify the neutron signature of a nuclear device, leveraging widely available sensor technologies.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: The Outer Space Treaty prohibits placing nuclear weapons in orbit, but verification has been challenging. The Van Allen radiation belts contain high-energy protons that, upon interacting with a nuclear warhead, produce a distinct neutron signal via spallation.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2512.20016v2">Verification of the Outer Space Treaty with Cosmic Protons - arXiv</a></li>

</ul>
</details>

**Tags**: `#arms control`, `#space security`, `#nuclear detection`, `#physics`, `#treaty verification`

---

<a id="item-8"></a>
## [Universal cell embedding foundation model trained on 36 million cells](https://www.nature.com/articles/s41586-026-10689-z) ⭐️ 9.0/10

A universal cell embedding foundation model has been trained on 36 million cells from hundreds of experiments, dozens of tissues, and eight species, published in Nature on July 8, 2026. This model represents a major breakthrough in computational biology, providing a foundational tool to capture cell organization and variation, with broad implications for biomedical research and personalized medicine. The model is trained on 36 million cells across multiple species, enabling it to learn universal cell representations that generalize across tissues and experimental conditions.

rss · Nature - Latest Research · Jul 8, 00:00

**Background**: Foundation models are large-scale machine learning models trained on vast datasets that can be adapted to a wide range of downstream tasks. In cell biology, such models aim to learn a universal representation of cell states from single-cell data, enabling tasks like cell type classification, perturbation prediction, and cross-species analysis.

**Tags**: `#foundation model`, `#cell biology`, `#computational biology`, `#deep learning`, `#bioinformatics`

---

<a id="item-9"></a>
## [Mistral Unveils Robostral Navigate for Map-Less Robot Navigation](https://mistral.ai/news/robostral-navigate/) ⭐️ 8.0/10

Mistral has released Robostral Navigate, a state-of-the-art deep learning model for map-less navigation in robotics, enabling robots to follow natural language directions without a pre-existing map. This advancement addresses the long-standing 'kidnapped robot problem' and could democratize robotics by enabling simpler, cheaper navigation systems for hobbyists and researchers, while also raising privacy considerations. The model appears to operate without a pre-captured map, relying solely on visual input and language commands, which is a significant technical leap. However, the model is not openly available, limiting immediate hobbyist use.

hackernews · ottomengis · Jul 8, 14:09 · [Discussion](https://news.ycombinator.com/item?id=48832212)

**Background**: Traditional robot navigation often requires a pre-built map of the environment, and when a robot loses its location (the 'kidnapped robot problem'), it struggles to navigate. Map-less navigation aims to allow robots to understand and follow directions without any prior map, using only sensors and AI.

**Discussion**: Commenters praised the map-less capability as impressive, noting it solves the kidnapped robot problem. Some expressed interest in hobbyist applications if the model were open-sourced, while others raised privacy concerns similar to those around location-from-image models like Stanford's PIGEON.

**Tags**: `#robotics`, `#navigation`, `#Mistral`, `#AI`, `#deep learning`

---

<a id="item-10"></a>
## [GitLost: Prompt Injection Leaks Private Repos via GitHub AI Agent](https://noma.security/blog/gitlost-how-we-tricked-githubs-ai-agent-into-leaking-private-repos/) ⭐️ 8.0/10

Researchers demonstrated a prompt injection attack that tricks GitHub's AI agent into leaking contents of private repositories when the agent has access to both public and private repos. This highlights a critical security vulnerability in agentic AI systems, where mixing trusted instructions with untrusted user input can lead to data breaches, similar to SQL injection in web applications. The attack uses a simple word like 'Additionally' to bypass GitHub's guardrails, proving that hard security boundaries inside an LLM context window are inherently fragile.

hackernews · ColinEberhardt · Jul 8, 05:25 · [Discussion](https://news.ycombinator.com/item?id=48827858)

**Background**: Prompt injection is a cybersecurity exploit where malicious inputs cause LLMs to behave unintentionally. In agentic AI, agents can execute actions based on prompts, making them vulnerable to indirect prompt injection from untrusted content.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://grokipedia.com/page/Agentic_AI_security">Agentic AI security</a></li>

</ul>
</details>

**Discussion**: Some commenters argue this is a misconfiguration issue, not a GitHub vulnerability, comparing it to running CI jobs with secrets on public PRs. Others note that prompt injection is a fundamental flaw in LLMs that cannot be fully fixed.

**Tags**: `#prompt injection`, `#AI security`, `#GitHub`, `#LLM vulnerabilities`, `#agentic AI`

---